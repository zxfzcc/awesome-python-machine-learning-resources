<!-- markdownlint-disable -->
<h1 align="center">
    python机器学习资源与工具库大全
    <br>
</h1>

<p align="center">
    <strong>python机器学习开源工具库资源大全，划分子版块并梳理排行，每周自动更新</strong>
</p>

<p align="center">
    <a href="#Contents" title="项目数量"><img src="https://img.shields.io/badge/projects-820-blue.svg?color=5ac4bf"></a>
    <a href="#Contribution" title="欢迎完善"><img src="https://img.shields.io/badge/contributions-welcome-green.svg"></a>
    <a href="https://github.com/ml-tooling/best-of-python/releases" title="最近更新"><img src="https://img.shields.io/github/release-date/ml-tooling/best-of-python?color=green&label=updated"></a>
</p>

本资源清单包含820个python机器学习相关的开源工具资源，这些热门工具总共分成32个不同的子板块，这些项目目前在github上已经收到2.8M个点赞。所有的工具资源每周会自动从GitHub和工具维护平台采集信息，并更新排行展示。本清单参考[best-of模板](https://github.com/best-of-lists/best-of)完成，内容参考了[awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning)，欢迎大家提PR丰富本清单。
## Contents

- [Machine Learning Frameworks](#machine-learning-frameworks) _54 projects_
- [Data Visualization](#data-visualization) _49 projects_
- [Text Data & NLP](#text-data--nlp) _82 projects_
- [Image Data](#image-data) _49 projects_
- [Graph Data](#graph-data) _29 projects_
- [Audio Data](#audio-data) _23 projects_
- [Geospatial Data](#geospatial-data) _22 projects_
- [Financial Data](#financial-data) _23 projects_
- [Time Series Data](#time-series-data) _20 projects_
- [Medical Data](#medical-data) _19 projects_
- [Optical Character Recognition](#optical-character-recognition) _11 projects_
- [Data Containers & Structures](#data-containers--structures) _28 projects_
- [Data Loading & Extraction](#data-loading--extraction) _23 projects_
- [Web Scraping & Crawling](#web-scraping--crawling) _1 projects_
- [Data Pipelines & Streaming](#data-pipelines--streaming) _36 projects_
- [Distributed Machine Learning](#distributed-machine-learning) _26 projects_
- [Hyperparameter Optimization & AutoML](#hyperparameter-optimization--automl) _45 projects_
- [Reinforcement Learning](#reinforcement-learning) _19 projects_
- [Recommender Systems](#recommender-systems) _13 projects_
- [Privacy Machine Learning](#privacy-machine-learning) _6 projects_
- [Workflow & Experiment Tracking](#workflow--experiment-tracking) _35 projects_
- [Model Serialization & Conversion](#model-serialization--conversion) _11 projects_
- [Model Interpretability](#model-interpretability) _46 projects_
- [Vector Similarity Search (ANN)](#vector-similarity-search-ann) _12 projects_
- [Probabilistics & Statistics](#probabilistics--statistics) _21 projects_
- [Adversarial Robustness](#adversarial-robustness) _7 projects_
- [GPU Utilities](#gpu-utilities) _18 projects_
- [Tensorflow Utilities](#tensorflow-utilities) _13 projects_
- [Sklearn Utilities](#sklearn-utilities) _17 projects_
- [Pytorch Utilities](#pytorch-utilities) _27 projects_
- [Database Clients](#database-clients) _1 projects_
- [Chinese NLP](#chinese-nlp) _2 projects_
- [Others](#others) _33 projects_

## Explanation
- 🥇🥈🥉&nbsp; Combined project-quality score
- ⭐️&nbsp; Star count from GitHub
- 🐣&nbsp; New project _(less than 6 months old)_
- 💤&nbsp; Inactive project _(6 months no activity)_
- 💀&nbsp; Dead project _(12 months no activity)_
- 📈📉&nbsp; Project is trending up or down
- ➕&nbsp; Project was recently added
- ❗️&nbsp; Warning _(e.g. missing/risky license)_
- 👨‍💻&nbsp; Contributors count from GitHub
- 🔀&nbsp; Fork count from GitHub
- 📋&nbsp; Issue count from GitHub
- ⏱️&nbsp; Last update timestamp on package manager
- 📥&nbsp; Download count from package manager
- 📦&nbsp; Number of dependent projects
- <img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13">&nbsp; Tensorflow related project
- <img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13">&nbsp; Sklearn related project
- <img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13">&nbsp; PyTorch related project
- <img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13">&nbsp; MxNet related project
- <img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13">&nbsp; Apache Spark related project
- <img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13">&nbsp; Jupyter related project
- <img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13">&nbsp; PaddlePaddle related project
- <img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13">&nbsp; Pandas related project

<br>

## Machine Learning Frameworks

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_General-purpose machine learning and deep learning frameworks._

<details><summary><b><a href="https://github.com/tensorflow/tensorflow">Tensorflow</a></b> (🥇44 ·  ⭐ 160K · 📈) - An Open Source Machine Learning Framework for Everyone. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/tensorflow) (👨‍💻 3.6K · 🔀 68K · 📦 130K · 📋 31K - 12% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/tensorflow/tensorflow
	```
- [PyPi](https://pypi.org/project/tensorflow) (📥 9.8M / month):
	```
	pip install tensorflow
	```
- [Conda](https://anaconda.org/conda-forge/tensorflow) (📥 2.5M · ⏱️ 12.04.2021):
	```
	conda install -c conda-forge tensorflow
	```
- [Docker Hub](https://hub.docker.com/r/tensorflow/tensorflow) (📥 51M · ⭐ 1.9K · ⏱️ 27.04.2021):
	```
	docker pull tensorflow/tensorflow
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/pytorch">PyTorch</a></b> (🥇40 ·  ⭐ 48K) - Tensors and Dynamic neural networks in Python with strong GPU.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/pytorch) (👨‍💻 2.6K · 🔀 12K · 📦 73K · 📋 20K - 30% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/pytorch/pytorch
	```
- [PyPi](https://pypi.org/project/torch) (📥 3.9M / month):
	```
	pip install torch
	```
- [Conda](https://anaconda.org/pytorch/pytorch) (📥 11M · ⏱️ 25.03.2021):
	```
	conda install -c pytorch pytorch
	```
</details>
<details><summary><b><a href="https://github.com/scikit-learn/scikit-learn">scikit-learn</a></b> (🥇37 ·  ⭐ 46K) - scikit-learn: machine learning in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/scikit-learn/scikit-learn) (👨‍💻 2.2K · 🔀 21K · 📥 690 · 📦 210K · 📋 8.5K - 18% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/scikit-learn/scikit-learn
	```
- [PyPi](https://pypi.org/project/scikit-learn) (📥 22M / month):
	```
	pip install scikit-learn
	```
- [Conda](https://anaconda.org/conda-forge/scikit-learn) (📥 7.8M · ⏱️ 21.01.2021):
	```
	conda install -c conda-forge scikit-learn
	```
</details>
<details><summary><b><a href="https://github.com/dmlc/xgboost">XGBoost</a></b> (🥇36 ·  ⭐ 21K) - Scalable, Portable and Distributed Gradient Boosting (GBDT, GBRT or.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/dmlc/xgboost) (👨‍💻 510 · 🔀 7.5K · 📥 2.2K · 📦 16K · 📋 4K - 6% open · ⏱️ 23.04.2021):

	```
	git clone https://github.com/dmlc/xgboost
	```
- [PyPi](https://pypi.org/project/xgboost) (📥 5.2M / month):
	```
	pip install xgboost
	```
- [Conda](https://anaconda.org/conda-forge/xgboost) (📥 1.6M · ⏱️ 09.03.2021):
	```
	conda install -c conda-forge xgboost
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/LightGBM">LightGBM</a></b> (🥇36 ·  ⭐ 12K) - A fast, distributed, high performance gradient boosting (GBT, GBDT, GBRT,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/LightGBM) (👨‍💻 220 · 🔀 3.2K · 📥 110K · 📦 6.7K · 📋 2.2K - 4% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/microsoft/LightGBM
	```
- [PyPi](https://pypi.org/project/lightgbm) (📥 3.7M / month):
	```
	pip install lightgbm
	```
- [Conda](https://anaconda.org/conda-forge/lightgbm) (📥 570K · ⏱️ 20.04.2021):
	```
	conda install -c conda-forge lightgbm
	```
</details>
<details><summary><b><a href="https://github.com/apache/spark">PySpark</a></b> (🥇35 ·  ⭐ 30K) - Apache Spark Python API. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/apache/spark) (👨‍💻 2.4K · 🔀 23K · 📦 580 · ⏱️ 28.04.2021):

	```
	git clone https://github.com/apache/spark
	```
- [PyPi](https://pypi.org/project/pyspark) (📥 9.8M / month):
	```
	pip install pyspark
	```
- [Conda](https://anaconda.org/conda-forge/pyspark) (📥 1M · ⏱️ 04.03.2021):
	```
	conda install -c conda-forge pyspark
	```
</details>
<details><summary><b><a href="https://github.com/apache/incubator-mxnet">MXNet</a></b> (🥈34 ·  ⭐ 19K) - Lightweight, Portable, Flexible Distributed/Mobile Deep Learning.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/apache/incubator-mxnet) (👨‍💻 960 · 🔀 6.5K · 📥 24K · 📦 2K · 📋 9.3K - 18% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/apache/incubator-mxnet
	```
- [PyPi](https://pypi.org/project/mxnet) (📥 250K / month):
	```
	pip install mxnet
	```
- [Conda](https://anaconda.org/anaconda/mxnet) (📥 6.1K · ⏱️ 29.02.2020):
	```
	conda install -c anaconda mxnet
	```
</details>
<details><summary><b><a href="https://github.com/PyTorchLightning/pytorch-lightning">pytorch-lightning</a></b> (🥈33 ·  ⭐ 13K) - The lightweight PyTorch wrapper for high-performance.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PyTorchLightning/pytorch-lightning) (👨‍💻 440 · 🔀 1.5K · 📥 1.9K · 📦 2.7K · 📋 3.2K - 7% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/PyTorchLightning/pytorch-lightning
	```
- [PyPi](https://pypi.org/project/pytorch-lightning) (📥 370K / month):
	```
	pip install pytorch-lightning
	```
- [Conda](https://anaconda.org/conda-forge/pytorch-lightning) (📥 120K · ⏱️ 27.04.2021):
	```
	conda install -c conda-forge pytorch-lightning
	```
</details>
<details><summary><b><a href="https://github.com/statsmodels/statsmodels">StatsModels</a></b> (🥈33 ·  ⭐ 6.3K) - Statsmodels: statistical modeling and econometrics in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/statsmodels/statsmodels) (👨‍💻 310 · 🔀 2.1K · 📥 25 · 📦 41K · 📋 4.2K - 45% open · ⏱️ 22.04.2021):

	```
	git clone https://github.com/statsmodels/statsmodels
	```
- [PyPi](https://pypi.org/project/statsmodels) (📥 4.1M / month):
	```
	pip install statsmodels
	```
- [Conda](https://anaconda.org/conda-forge/statsmodels) (📥 3.9M · ⏱️ 15.02.2021):
	```
	conda install -c conda-forge statsmodels
	```
</details>
<details><summary><b><a href="https://github.com/davisking/dlib">dlib</a></b> (🥈32 ·  ⭐ 10K) - A toolkit for making real world machine learning and data analysis.. <code><a href="https://tldrlegal.com/search?q=BSL-1.0">❗️BSL-1.0</a></code></summary>

- [GitHub](https://github.com/davisking/dlib) (👨‍💻 170 · 🔀 2.5K · 📥 25K · 📦 9.4K · 📋 1.9K - 2% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/davisking/dlib
	```
- [PyPi](https://pypi.org/project/dlib) (📥 120K / month):
	```
	pip install dlib
	```
- [Conda](https://anaconda.org/conda-forge/dlib) (📥 300K · ⏱️ 03.04.2021):
	```
	conda install -c conda-forge dlib
	```
</details>
<details><summary><b><a href="https://github.com/explosion/thinc">Thinc</a></b> (🥈32 ·  ⭐ 2.3K) - A refreshing functional take on deep learning, compatible with your favorite.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/explosion/thinc) (👨‍💻 36 · 🔀 200 · 📦 13K · 📋 100 - 11% open · ⏱️ 20.04.2021):

	```
	git clone https://github.com/explosion/thinc
	```
- [PyPi](https://pypi.org/project/thinc) (📥 1.9M / month):
	```
	pip install thinc
	```
- [Conda](https://anaconda.org/conda-forge/thinc) (📥 1.2M · ⏱️ 23.04.2021):
	```
	conda install -c conda-forge thinc
	```
</details>
<details><summary><b><a href="https://github.com/apache/flink">PyFlink</a></b> (🥈31 ·  ⭐ 16K) - Apache Flink Python API. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/apache/flink) (👨‍💻 1.3K · 🔀 8.7K · 📦 280 · ⏱️ 27.04.2021):

	```
	git clone https://github.com/apache/flink
	```
- [PyPi](https://pypi.org/project/apache-flink) (📥 8.2K / month):
	```
	pip install apache-flink
	```
</details>
<details><summary><b><a href="https://github.com/Theano/Theano">Theano</a></b> (🥈31 ·  ⭐ 9.4K) - Theano is a Python library that allows you to define, optimize,.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/Theano/Theano) (👨‍💻 380 · 🔀 2.4K · 📦 11K · 📋 2.7K - 21% open · ⏱️ 13.04.2021):

	```
	git clone https://github.com/Theano/Theano
	```
- [PyPi](https://pypi.org/project/theano) (📥 290K / month):
	```
	pip install theano
	```
- [Conda](https://anaconda.org/conda-forge/theano) (📥 1.5M · ⏱️ 21.01.2021):
	```
	conda install -c conda-forge theano
	```
</details>
<details><summary><b><a href="https://github.com/chainer/chainer">Chainer</a></b> (🥈31 ·  ⭐ 5.6K) - A flexible framework of neural networks for deep learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/chainer/chainer) (👨‍💻 320 · 🔀 1.3K · 📦 2.1K · 📋 2K - 0% open · ⏱️ 17.02.2021):

	```
	git clone https://github.com/chainer/chainer
	```
- [PyPi](https://pypi.org/project/chainer) (📥 26K / month):
	```
	pip install chainer
	```
</details>
<details><summary><b><a href="https://github.com/PaddlePaddle/Paddle">PaddlePaddle</a></b> (🥈30 ·  ⭐ 15K) - PArallel Distributed Deep LEarning: Machine Learning.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PaddlePaddle/Paddle) (👨‍💻 530 · 🔀 3.6K · 📥 15K · 📦 38 · 📋 13K - 15% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/PaddlePaddle/Paddle
	```
- [PyPi](https://pypi.org/project/paddlepaddle) (📥 14K / month):
	```
	pip install paddlepaddle
	```
</details>
<details><summary><b><a href="https://github.com/VowpalWabbit/vowpal_wabbit">Vowpal Wabbit</a></b> (🥈30 ·  ⭐ 7.5K) - Vowpal Wabbit is a machine learning system which pushes the.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/VowpalWabbit/vowpal_wabbit) (👨‍💻 300 · 🔀 1.6K · 📦 120 · 📋 1K - 12% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/VowpalWabbit/vowpal_wabbit
	```
- [PyPi](https://pypi.org/project/vowpalwabbit) (📥 26K / month):
	```
	pip install vowpalwabbit
	```
</details>
<details><summary><b><a href="https://github.com/deepmind/sonnet">Sonnet</a></b> (🥈29 ·  ⭐ 8.8K) - TensorFlow-based neural network library. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deepmind/sonnet) (👨‍💻 51 · 🔀 1.2K · 📦 560 · 📋 150 - 10% open · ⏱️ 15.03.2021):

	```
	git clone https://github.com/deepmind/sonnet
	```
- [PyPi](https://pypi.org/project/dm-sonnet) (📥 82K / month):
	```
	pip install dm-sonnet
	```
- [Conda](https://anaconda.org/conda-forge/sonnet) (📥 8.9K · ⏱️ 14.11.2020):
	```
	conda install -c conda-forge sonnet
	```
</details>
<details><summary><b><a href="https://github.com/fastai/fastai">Fastai</a></b> (🥈28 ·  ⭐ 21K) - The fastai deep learning library. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/fastai/fastai) (👨‍💻 150 · 🔀 6.8K · 📋 1.4K - 5% open · ⏱️ 22.04.2021):

	```
	git clone https://github.com/fastai/fastai
	```
- [PyPi](https://pypi.org/project/fastai) (📥 200K / month):
	```
	pip install fastai
	```
</details>
<details><summary><b><a href="https://github.com/google/jax">jax</a></b> (🥈28 ·  ⭐ 12K) - Composable transformations of Python+NumPy programs: differentiate,.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/google/jax) (👨‍💻 280 · 🔀 1.1K · 📦 1.5K · 📋 2.2K - 29% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/google/jax
	```
- [PyPi](https://pypi.org/project/jax) (📥 200K / month):
	```
	pip install jax
	```
- [Conda](https://anaconda.org/conda-forge/jaxlib) (📥 110K · ⏱️ 08.04.2021):
	```
	conda install -c conda-forge jaxlib
	```
</details>
<details><summary><b><a href="https://github.com/apple/turicreate">Turi Create</a></b> (🥈28 ·  ⭐ 10K) - Turi Create simplifies the development of custom machine learning.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/apple/turicreate) (👨‍💻 82 · 🔀 1.1K · 📥 3.9K · 📦 240 · 📋 1.7K - 26% open · ⏱️ 31.03.2021):

	```
	git clone https://github.com/apple/turicreate
	```
- [PyPi](https://pypi.org/project/turicreate) (📥 29K / month):
	```
	pip install turicreate
	```
</details>
<details><summary><b><a href="https://github.com/catboost/catboost">Catboost</a></b> (🥈28 ·  ⭐ 5.8K) - A fast, scalable, high performance Gradient Boosting on Decision.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/catboost/catboost) (👨‍💻 780 · 🔀 850 · 📥 54K · 📋 1.4K - 21% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/catboost/catboost
	```
- [PyPi](https://pypi.org/project/catboost) (📥 2.8M / month):
	```
	pip install catboost
	```
- [Conda](https://anaconda.org/conda-forge/catboost) (📥 660K · ⏱️ 12.04.2021):
	```
	conda install -c conda-forge catboost
	```
</details>
<details><summary><b><a href="https://github.com/google/flax">Flax</a></b> (🥈28 ·  ⭐ 1.7K) - Flax is a neural network library for JAX that is designed for.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code>jax</code></summary>

- [GitHub](https://github.com/google/flax) (👨‍💻 87 · 🔀 190 · 📥 23 · 📦 140 · 📋 310 - 37% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/google/flax
	```
- [PyPi](https://pypi.org/project/flax) (📥 110K / month):
	```
	pip install flax
	```
</details>
<details><summary><b><a href="https://github.com/keras-team/keras">Keras</a></b> (🥉27 ·  ⭐ 51K) - Deep Learning for humans. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/keras-team/keras) (👨‍💻 910 · 🔀 18K · 📋 10K - 30% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/keras-team/keras
	```
- [PyPi](https://pypi.org/project/keras) (📥 3.2M / month):
	```
	pip install keras
	```
- [Conda](https://anaconda.org/conda-forge/keras) (📥 1.6M · ⏱️ 19.04.2021):
	```
	conda install -c conda-forge keras
	```
</details>
<details><summary><b><a href="https://github.com/tflearn/tflearn">TFlearn</a></b> (🥉27 ·  ⭐ 9.5K) - Deep learning library featuring a higher-level API for.. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tflearn/tflearn) (👨‍💻 130 · 🔀 2.3K · 📦 3.2K · 📋 910 - 60% open · ⏱️ 30.11.2020):

	```
	git clone https://github.com/tflearn/tflearn
	```
- [PyPi](https://pypi.org/project/tflearn) (📥 17K / month):
	```
	pip install tflearn
	```
</details>
<details><summary><b><a href="https://github.com/tensorpack/tensorpack">tensorpack</a></b> (🥉27 ·  ⭐ 6K) - A Neural Net Training Interface on TensorFlow, with focus on.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorpack/tensorpack) (👨‍💻 55 · 🔀 1.7K · 📥 120 · 📦 740 · 📋 1.3K - 0% open · ⏱️ 19.04.2021):

	```
	git clone https://github.com/tensorpack/tensorpack
	```
- [PyPi](https://pypi.org/project/tensorpack) (📥 16K / month):
	```
	pip install tensorpack
	```
</details>
<details><summary><b><a href="https://github.com/skorch-dev/skorch">skorch</a></b> (🥉27 ·  ⭐ 3.9K) - A scikit-learn compatible neural network library that wraps.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/skorch-dev/skorch) (👨‍💻 39 · 🔀 280 · 📦 300 · 📋 370 - 11% open · ⏱️ 23.04.2021):

	```
	git clone https://github.com/skorch-dev/skorch
	```
- [PyPi](https://pypi.org/project/skorch) (📥 15K / month):
	```
	pip install skorch
	```
- [Conda](https://anaconda.org/conda-forge/skorch) (📥 250K · ⏱️ 24.03.2021):
	```
	conda install -c conda-forge skorch
	```
</details>
<details><summary><b><a href="https://github.com/clab/dynet">dyNET</a></b> (🥉27 ·  ⭐ 3.2K) - DyNet: The Dynamic Neural Network Toolkit. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/clab/dynet) (👨‍💻 160 · 🔀 660 · 📥 2.7K · 📦 180 · 📋 910 - 27% open · ⏱️ 27.01.2021):

	```
	git clone https://github.com/clab/dynet
	```
- [PyPi](https://pypi.org/project/dyNET) (📥 17K / month):
	```
	pip install dyNET
	```
</details>
<details><summary><b><a href="https://github.com/jina-ai/jina">Jina</a></b> (🥉27 ·  ⭐ 3.1K) - An easier way to build neural search on the cloud. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/jina-ai/jina) (👨‍💻 93 · 🔀 430 · 📦 59 · 📋 750 - 7% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/jina-ai/jina
	```
- [PyPi](https://pypi.org/project/jina) (📥 15K / month):
	```
	pip install jina
	```
- [Docker Hub](https://hub.docker.com/r/jinaai/jina) (📥 250K · ⭐ 2 · ⏱️ 27.04.2021):
	```
	docker pull jinaai/jina
	```
</details>
<details><summary><b><a href="https://github.com/ludwig-ai/ludwig">Ludwig</a></b> (🥉26 ·  ⭐ 7.7K) - Ludwig is a toolbox that allows to train and evaluate deep.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/ludwig-ai/ludwig) (👨‍💻 91 · 🔀 860 · 📦 85 · 📋 540 - 20% open · ⏱️ 25.04.2021):

	```
	git clone https://github.com/ludwig-ai/ludwig
	```
- [PyPi](https://pypi.org/project/ludwig) (📥 2.1K / month):
	```
	pip install ludwig
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/ignite">Ignite</a></b> (🥉26 ·  ⭐ 3.5K) - High-level library to help with training and evaluating neural.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/ignite) (👨‍💻 140 · 🔀 450 · 📦 850 · 📋 800 - 12% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/pytorch/ignite
	```
- [PyPi](https://pypi.org/project/pytorch-ignite) (📥 56K / month):
	```
	pip install pytorch-ignite
	```
- [Conda](https://anaconda.org/pytorch/ignite) (📥 59K · ⏱️ 03.03.2021):
	```
	conda install -c pytorch ignite
	```
</details>
<details><summary><b><a href="https://github.com/numenta/nupic">NuPIC</a></b> (🥉25 ·  ⭐ 6.2K · 💀) - Numenta Platform for Intelligent Computing is an implementation.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/numenta/nupic) (👨‍💻 120 · 🔀 1.6K · 📦 95 · 📋 1.8K - 25% open · ⏱️ 23.10.2019):

	```
	git clone https://github.com/numenta/nupic
	```
- [PyPi](https://pypi.org/project/nupic) (📥 3.1K / month):
	```
	pip install nupic
	```
</details>
<details><summary><b><a href="https://github.com/amaiya/ktrain">ktrain</a></b> (🥉25 ·  ⭐ 800) - ktrain is a Python library that makes deep learning and AI more.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/amaiya/ktrain) (👨‍💻 12 · 🔀 190 · 📦 150 · 📋 340 - 2% open · ⏱️ 26.03.2021):

	```
	git clone https://github.com/amaiya/ktrain
	```
- [PyPi](https://pypi.org/project/ktrain) (📥 20K / month):
	```
	pip install ktrain
	```
</details>
<details><summary><b><a href="https://github.com/aksnzhy/xlearn">xLearn</a></b> (🥉24 ·  ⭐ 2.9K · 💀) - High performance, easy-to-use, and scalable machine learning (ML).. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/aksnzhy/xlearn) (👨‍💻 30 · 🔀 500 · 📥 2.5K · 📦 52 · 📋 290 - 62% open · ⏱️ 03.03.2020):

	```
	git clone https://github.com/aksnzhy/xlearn
	```
- [PyPi](https://pypi.org/project/xlearn) (📥 3.5K / month):
	```
	pip install xlearn
	```
</details>
<details><summary><b><a href="https://github.com/arogozhnikov/einops">einops</a></b> (🥉24 ·  ⭐ 2.9K) - Deep learning operations reinvented (for pytorch, tensorflow, jax and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/arogozhnikov/einops) (👨‍💻 11 · 🔀 97 · 📦 460 · 📋 67 - 31% open · ⏱️ 03.04.2021):

	```
	git clone https://github.com/arogozhnikov/einops
	```
- [PyPi](https://pypi.org/project/einops) (📥 89K / month):
	```
	pip install einops
	```
- [Conda](https://anaconda.org/conda-forge/einops) (📥 4.6K · ⏱️ 15.10.2020):
	```
	conda install -c conda-forge einops
	```
</details>
<details><summary><b><a href="https://github.com/ROCmSoftwarePlatform/tensorflow-upstream">tensorflow-upstream</a></b> (🥉24 ·  ⭐ 550) - TensorFlow ROCm port. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/ROCmSoftwarePlatform/tensorflow-upstream) (👨‍💻 3.6K · 🔀 65 · 📥 16 · 📋 280 - 13% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/ROCmSoftwarePlatform/tensorflow-upstream
	```
- [PyPi](https://pypi.org/project/tensorflow-rocm) (📥 3.3K / month):
	```
	pip install tensorflow-rocm
	```
</details>
<details><summary><b><a href="https://github.com/NervanaSystems/neon">neon</a></b> (🥉23 ·  ⭐ 3.9K · 💀) - Intel Nervana reference deep learning framework committed to best.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/NervanaSystems/neon) (👨‍💻 110 · 🔀 810 · 📥 310 · 📦 45 · 📋 390 - 21% open · ⏱️ 22.05.2019):

	```
	git clone https://github.com/NervanaSystems/neon
	```
- [PyPi](https://pypi.org/project/nervananeon) (📥 160 / month):
	```
	pip install nervananeon
	```
</details>
<details><summary><b><a href="https://github.com/mlpack/mlpack">mlpack</a></b> (🥉23 ·  ⭐ 3.6K) - mlpack: a scalable C++ machine learning library --. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/mlpack/mlpack) (👨‍💻 270 · 🔀 1.3K · 📋 1.3K - 6% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/mlpack/mlpack
	```
- [PyPi](https://pypi.org/project/mlpack) (📥 490 / month):
	```
	pip install mlpack
	```
- [Conda](https://anaconda.org/conda-forge/mlpack) (📥 73K · ⏱️ 29.10.2020):
	```
	conda install -c conda-forge mlpack
	```
</details>
<details><summary><b><a href="https://github.com/shogun-toolbox/shogun">SHOGUN</a></b> (🥉23 ·  ⭐ 2.8K) - Unified and efficient Machine Learning. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/shogun-toolbox/shogun) (👨‍💻 250 · 🔀 1K · 📋 1.5K - 28% open · ⏱️ 08.12.2020):

	```
	git clone https://github.com/shogun-toolbox/shogun
	```
- [Conda](https://anaconda.org/conda-forge/shogun) (📥 98K · ⏱️ 25.06.2018):
	```
	conda install -c conda-forge shogun
	```
- [Docker Hub](https://hub.docker.com/r/shogun/shogun) (📥 1.4K · ⭐ 1 · ⏱️ 31.01.2019):
	```
	docker pull shogun/shogun
	```
</details>
<details><summary><b><a href="https://github.com/sony/nnabla">Neural Network Libraries</a></b> (🥉23 ·  ⭐ 2.4K) - Neural Network Libraries. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/sony/nnabla) (👨‍💻 58 · 🔀 290 · 📥 520 · 📋 47 - 36% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/sony/nnabla
	```
- [PyPi](https://pypi.org/project/nnabla) (📥 4.8K / month):
	```
	pip install nnabla
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/CNTK">CNTK</a></b> (🥉22 ·  ⭐ 17K · 💀) - Microsoft Cognitive Toolkit (CNTK), an open source deep-learning.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/microsoft/CNTK) (👨‍💻 270 · 🔀 4.3K · 📥 14K · 📋 3.3K - 23% open · ⏱️ 31.03.2020):

	```
	git clone https://github.com/microsoft/CNTK
	```
- [PyPi](https://pypi.org/project/cntk) (📥 1.9K / month):
	```
	pip install cntk
	```
</details>
<details><summary><b><a href="https://github.com/google/neural-tangents">Neural Tangents</a></b> (🥉22 ·  ⭐ 1.4K) - Fast and Easy Infinite Neural Networks in Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google/neural-tangents) (👨‍💻 18 · 🔀 150 · 📥 110 · 📦 14 · 📋 79 - 29% open · ⏱️ 21.04.2021):

	```
	git clone https://github.com/google/neural-tangents
	```
- [PyPi](https://pypi.org/project/neural-tangents) (📥 720 / month):
	```
	pip install neural-tangents
	```
</details>
<details><summary><b><a href="https://github.com/nubank/fklearn">fklearn</a></b> (🥉22 ·  ⭐ 1.3K) - fklearn: Functional Machine Learning. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/nubank/fklearn) (👨‍💻 37 · 🔀 140 · 📦 10 · 📋 39 - 48% open · ⏱️ 09.02.2021):

	```
	git clone https://github.com/nubank/fklearn
	```
- [PyPi](https://pypi.org/project/fklearn) (📥 7.9K / month):
	```
	pip install fklearn
	```
</details>
<details><summary><b><a href="https://github.com/itdxer/neupy">NeuPy</a></b> (🥉22 ·  ⭐ 680 · 💀) - NeuPy is a Tensorflow based python library for prototyping and building.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/itdxer/neupy) (👨‍💻 6 · 🔀 140 · 📦 100 · 📋 260 - 9% open · ⏱️ 02.09.2019):

	```
	git clone https://github.com/itdxer/neupy
	```
- [PyPi](https://pypi.org/project/neupy) (📥 1.9K / month):
	```
	pip install neupy
	```
</details>
<details><summary><b><a href="https://github.com/XiaoMi/mace">mace</a></b> (🥉21 ·  ⭐ 4.3K) - MACE is a deep learning inference framework optimized for mobile.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/XiaoMi/mace) (👨‍💻 57 · 🔀 750 · 📥 1.3K · 📋 640 - 5% open · ⏱️ 22.04.2021):

	```
	git clone https://github.com/XiaoMi/mace
	```
</details>
<details><summary><b><a href="https://github.com/Lasagne/Lasagne">Lasagne</a></b> (🥉21 ·  ⭐ 3.8K · 💀) - Lightweight library to build and train neural networks in.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/Lasagne/Lasagne) (👨‍💻 72 · 🔀 930 · 📦 810 · 📋 520 - 22% open · ⏱️ 20.11.2019):

	```
	git clone https://github.com/Lasagne/Lasagne
	```
- [PyPi](https://pypi.org/project/lasagne) (📥 2.8K / month):
	```
	pip install lasagne
	```
</details>
<details><summary><b><a href="https://github.com/Xtra-Computing/thundersvm">ThunderSVM</a></b> (🥉20 ·  ⭐ 1.3K) - ThunderSVM: A Fast SVM Library on GPUs and CPUs. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Xtra-Computing/thundersvm) (👨‍💻 33 · 🔀 170 · 📥 2.2K · 📋 190 - 23% open · ⏱️ 10.02.2021):

	```
	git clone https://github.com/Xtra-Computing/thundersvm
	```
- [PyPi](https://pypi.org/project/thundersvm) (📥 600 / month):
	```
	pip install thundersvm
	```
</details>
<details><summary><b><a href="https://github.com/deepmind/dm-haiku">Haiku</a></b> (🥉20 ·  ⭐ 1.1K) - JAX-based neural network library. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/deepmind/dm-haiku) (👨‍💻 41 · 🔀 75 · 📦 82 · 📋 78 - 20% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/deepmind/dm-haiku
	```
</details>
<details><summary><b><a href="https://github.com/pytorchbearer/torchbearer">Torchbearer</a></b> (🥉20 ·  ⭐ 600) - torchbearer: A model fitting library for PyTorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorchbearer/torchbearer) (👨‍💻 13 · 🔀 64 · 📦 41 · 📋 240 - 3% open · ⏱️ 26.03.2021):

	```
	git clone https://github.com/pytorchbearer/torchbearer
	```
- [PyPi](https://pypi.org/project/torchbearer) (📥 3.5K / month):
	```
	pip install torchbearer
	```
</details>
<details><summary><b><a href="https://github.com/google/objax">Objax</a></b> (🥉20 ·  ⭐ 590) - Objax is a machine learning framework that provides an Object.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code>jax</code></summary>

- [GitHub](https://github.com/google/objax) (👨‍💻 20 · 🔀 44 · 📦 12 · 📋 87 - 40% open · ⏱️ 21.04.2021):

	```
	git clone https://github.com/google/objax
	```
- [PyPi](https://pypi.org/project/objax) (📥 470 / month):
	```
	pip install objax
	```
</details>
<details><summary><b><a href="https://github.com/mindsdb/mindsdb">MindsDB</a></b> (🥉19 ·  ⭐ 3.7K) - Predictive AI layer for existing databases. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/mindsdb/mindsdb) (👨‍💻 56 · 🔀 440 · 📋 570 - 8% open · ⏱️ 23.04.2021):

	```
	git clone https://github.com/mindsdb/mindsdb
	```
- [PyPi](https://pypi.org/project/mindsdb) (📥 3.8K / month):
	```
	pip install mindsdb
	```
</details>
<details><summary><b><a href="https://github.com/Xtra-Computing/thundergbm">ThunderGBM</a></b> (🥉17 ·  ⭐ 590) - ThunderGBM: Fast GBDTs and Random Forests on GPUs. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Xtra-Computing/thundergbm) (👨‍💻 10 · 🔀 75 · 📋 49 - 42% open · ⏱️ 05.01.2021):

	```
	git clone https://github.com/Xtra-Computing/thundergbm
	```
- [PyPi](https://pypi.org/project/thundergbm) (📥 160 / month):
	```
	pip install thundergbm
	```
</details>
<details><summary><b><a href="https://github.com/poets-ai/elegy">elegy</a></b> (🥉17 ·  ⭐ 210) - Elegy is a framework-agnostic Trainer interface for the Jax.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code>jax</code></summary>

- [GitHub](https://github.com/poets-ai/elegy) (👨‍💻 13 · 🔀 11 · 📋 54 - 33% open · ⏱️ 01.04.2021):

	```
	git clone https://github.com/poets-ai/elegy
	```
- [PyPi](https://pypi.org/project/elegy) (📥 660 / month):
	```
	pip install elegy
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/StarSpace">StarSpace</a></b> (🥉14 ·  ⭐ 3.6K · 💀) - Learning embeddings for classification, retrieval and ranking. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebookresearch/StarSpace) (👨‍💻 17 · 🔀 480 · 📋 190 - 23% open · ⏱️ 13.12.2019):

	```
	git clone https://github.com/facebookresearch/StarSpace
	```
</details>
<details><summary><b><a href="https://github.com/neoml-lib/neoml">NeoML</a></b> (🥉14 ·  ⭐ 590) - Machine learning framework for both deep learning and traditional.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/neoml-lib/neoml) (👨‍💻 21 · 🔀 84 · 📋 30 - 56% open · ⏱️ 24.04.2021):

	```
	git clone https://github.com/neoml-lib/neoml
	```
</details>
<br>

## Data Visualization

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_General-purpose and task-specific data visualization libraries._

<details><summary><b><a href="https://github.com/matplotlib/matplotlib">Matplotlib</a></b> (🥇39 ·  ⭐ 14K) - matplotlib: plotting with Python. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/matplotlib/matplotlib) (👨‍💻 1.2K · 🔀 5.6K · 📦 360K · 📋 7.6K - 18% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/matplotlib/matplotlib
	```
- [PyPi](https://pypi.org/project/matplotlib) (📥 20M / month):
	```
	pip install matplotlib
	```
- [Conda](https://anaconda.org/conda-forge/matplotlib) (📥 8.7M · ⏱️ 31.03.2021):
	```
	conda install -c conda-forge matplotlib
	```
</details>
<details><summary><b><a href="https://github.com/mwaskom/seaborn">Seaborn</a></b> (🥇37 ·  ⭐ 8.4K) - Statistical data visualization using matplotlib. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/mwaskom/seaborn) (👨‍💻 150 · 🔀 1.4K · 📥 160 · 📦 92K · 📋 1.8K - 5% open · ⏱️ 23.04.2021):

	```
	git clone https://github.com/mwaskom/seaborn
	```
- [PyPi](https://pypi.org/project/seaborn) (📥 4.9M / month):
	```
	pip install seaborn
	```
- [Conda](https://anaconda.org/conda-forge/seaborn) (📥 2.3M · ⏱️ 28.01.2021):
	```
	conda install -c conda-forge seaborn
	```
</details>
<details><summary><b><a href="https://github.com/plotly/dash">dash</a></b> (🥇35 ·  ⭐ 14K · 📈) - Analytical Web Apps for Python, R, Julia, and Jupyter. No JavaScript.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/plotly/dash) (👨‍💻 74 · 🔀 1.4K · 📦 20K · 📋 990 - 42% open · ⏱️ 08.04.2021):

	```
	git clone https://github.com/plotly/dash
	```
- [PyPi](https://pypi.org/project/dash) (📥 450K / month):
	```
	pip install dash
	```
- [Conda](https://anaconda.org/conda-forge/dash) (📥 240K · ⏱️ 10.04.2021):
	```
	conda install -c conda-forge dash
	```
</details>
<details><summary><b><a href="https://github.com/bokeh/bokeh">Bokeh</a></b> (🥇31 ·  ⭐ 15K) - Interactive Data Visualization in the browser, from Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/bokeh/bokeh) (👨‍💻 560 · 🔀 3.6K · 📦 33K · 📋 6.5K - 9% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/bokeh/bokeh
	```
- [PyPi](https://pypi.org/project/bokeh) (📥 1.5M / month):
	```
	pip install bokeh
	```
- [Conda](https://anaconda.org/conda-forge/bokeh) (📥 4.3M · ⏱️ 08.04.2021):
	```
	conda install -c conda-forge bokeh
	```
</details>
<details><summary><b><a href="https://github.com/plotly/plotly.py">Plotly</a></b> (🥇31 ·  ⭐ 9.4K) - The interactive graphing library for Python (includes Plotly Express). <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/plotly/plotly.py) (👨‍💻 170 · 🔀 1.8K · 📦 5 · 📋 1.9K - 43% open · ⏱️ 24.04.2021):

	```
	git clone https://github.com/plotly/plotly.py
	```
- [PyPi](https://pypi.org/project/plotly) (📥 5.3M / month):
	```
	pip install plotly
	```
- [Conda](https://anaconda.org/conda-forge/plotly) (📥 1.3M · ⏱️ 12.01.2021):
	```
	conda install -c conda-forge plotly
	```
- [NPM](https://www.npmjs.com/package/plotlywidget) (📥 110K / month):
	```
	npm install plotlywidget
	```
</details>
<details><summary><b><a href="https://github.com/altair-viz/altair">Altair</a></b> (🥇31 ·  ⭐ 6.6K) - Declarative statistical visualization library for Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/altair-viz/altair) (👨‍💻 130 · 🔀 560 · 📦 10K · 📋 1.5K - 13% open · ⏱️ 04.04.2021):

	```
	git clone https://github.com/altair-viz/altair
	```
- [PyPi](https://pypi.org/project/altair) (📥 1.2M / month):
	```
	pip install altair
	```
- [Conda](https://anaconda.org/conda-forge/altair) (📥 700K · ⏱️ 01.04.2020):
	```
	conda install -c conda-forge altair
	```
</details>
<details><summary><b><a href="https://github.com/lmcinnes/umap">UMAP</a></b> (🥇31 ·  ⭐ 4.7K) - Uniform Manifold Approximation and Projection. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/lmcinnes/umap) (👨‍💻 79 · 🔀 500 · 📦 2.8K · 📋 480 - 48% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/lmcinnes/umap
	```
- [PyPi](https://pypi.org/project/umap-learn) (📥 460K / month):
	```
	pip install umap-learn
	```
</details>
<details><summary><b><a href="https://github.com/amueller/word_cloud">wordcloud</a></b> (🥈30 ·  ⭐ 8K) - A little word cloud generator in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/amueller/word_cloud) (👨‍💻 61 · 🔀 2K · 📦 10K · 📋 430 - 18% open · ⏱️ 01.03.2021):

	```
	git clone https://github.com/amueller/word_cloud
	```
- [PyPi](https://pypi.org/project/wordcloud) (📥 410K / month):
	```
	pip install wordcloud
	```
- [Conda](https://anaconda.org/conda-forge/wordcloud) (📥 210K · ⏱️ 14.01.2021):
	```
	conda install -c conda-forge wordcloud
	```
</details>
<details><summary><b><a href="https://github.com/pandas-profiling/pandas-profiling">pandas-profiling</a></b> (🥈29 ·  ⭐ 7.2K) - Create HTML profiling reports from pandas DataFrame.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pandas-profiling/pandas-profiling) (👨‍💻 75 · 🔀 1.1K · 📦 3.8K · 📋 460 - 16% open · ⏱️ 19.04.2021):

	```
	git clone https://github.com/pandas-profiling/pandas-profiling
	```
- [PyPi](https://pypi.org/project/pandas-profiling) (📥 370K / month):
	```
	pip install pandas-profiling
	```
- [Conda](https://anaconda.org/conda-forge/pandas-profiling) (📥 120K · ⏱️ 20.02.2021):
	```
	conda install -c conda-forge pandas-profiling
	```
</details>
<details><summary><b><a href="https://github.com/pyecharts/pyecharts">pyecharts</a></b> (🥈28 ·  ⭐ 11K) - Python Echarts Plotting Library. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pyecharts/pyecharts) (👨‍💻 30 · 🔀 2.4K · 📦 1.6K · 📋 1.4K - 2% open · ⏱️ 19.01.2021):

	```
	git clone https://github.com/pyecharts/pyecharts
	```
- [PyPi](https://pypi.org/project/pyecharts) (📥 46K / month):
	```
	pip install pyecharts
	```
</details>
<details><summary><b><a href="https://github.com/has2k1/plotnine">plotnine</a></b> (🥈28 ·  ⭐ 2.7K) - A grammar of graphics for Python. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/has2k1/plotnine) (👨‍💻 82 · 🔀 140 · 📦 1.8K · 📋 430 - 14% open · ⏱️ 20.04.2021):

	```
	git clone https://github.com/has2k1/plotnine
	```
- [PyPi](https://pypi.org/project/plotnine) (📥 160K / month):
	```
	pip install plotnine
	```
- [Conda](https://anaconda.org/conda-forge/plotnine) (📥 100K · ⏱️ 25.03.2021):
	```
	conda install -c conda-forge plotnine
	```
</details>
<details><summary><b><a href="https://github.com/bqplot/bqplot">bqplot</a></b> (🥈27 ·  ⭐ 3.1K · 📉) - Plotting library for IPython/Jupyter notebooks. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/bqplot/bqplot) (👨‍💻 51 · 🔀 400 · 📦 24 · 📋 530 - 36% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/bqplot/bqplot
	```
- [PyPi](https://pypi.org/project/bqplot) (📥 35K / month):
	```
	pip install bqplot
	```
- [Conda](https://anaconda.org/conda-forge/bqplot) (📥 590K · ⏱️ 21.04.2021):
	```
	conda install -c conda-forge bqplot
	```
- [NPM](https://www.npmjs.com/package/bqplot) (📥 16K / month):
	```
	npm install bqplot
	```
</details>
<details><summary><b><a href="https://github.com/ResidentMario/missingno">missingno</a></b> (🥈27 ·  ⭐ 2.8K) - Missing data visualization module for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ResidentMario/missingno) (👨‍💻 16 · 🔀 350 · 📦 3.5K · 📋 100 - 16% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/ResidentMario/missingno
	```
- [PyPi](https://pypi.org/project/missingno) (📥 320K / month):
	```
	pip install missingno
	```
- [Conda](https://anaconda.org/conda-forge/missingno) (📥 88K · ⏱️ 15.02.2020):
	```
	conda install -c conda-forge missingno
	```
</details>
<details><summary><b><a href="https://github.com/vispy/vispy">VisPy</a></b> (🥈27 ·  ⭐ 2.6K) - High-performance interactive 2D/3D data visualization library. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/vispy/vispy) (👨‍💻 150 · 🔀 540 · 📦 490 · 📋 1.1K - 28% open · ⏱️ 22.04.2021):

	```
	git clone https://github.com/vispy/vispy
	```
- [PyPi](https://pypi.org/project/vispy) (📥 35K / month):
	```
	pip install vispy
	```
- [Conda](https://anaconda.org/conda-forge/vispy) (📥 140K · ⏱️ 13.01.2021):
	```
	conda install -c conda-forge vispy
	```
- [NPM](https://www.npmjs.com/package/vispy) (📥 81 / month):
	```
	npm install vispy
	```
</details>
<details><summary><b><a href="https://github.com/xflr6/graphviz">Graphviz</a></b> (🥈27 ·  ⭐ 980) - Simple Python interface for Graphviz. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/xflr6/graphviz) (👨‍💻 15 · 🔀 140 · 📦 20K · 📋 100 - 4% open · ⏱️ 14.03.2021):

	```
	git clone https://github.com/xflr6/graphviz
	```
- [PyPi](https://pypi.org/project/graphviz) (📥 6.1M / month):
	```
	pip install graphviz
	```
</details>
<details><summary><b><a href="https://github.com/pyvista/pyvista">PyVista</a></b> (🥈27 ·  ⭐ 780) - 3D plotting and mesh analysis through a streamlined interface for the.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pyvista/pyvista) (👨‍💻 56 · 🔀 150 · 📥 71 · 📦 300 · 📋 440 - 30% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/pyvista/pyvista
	```
- [PyPi](https://pypi.org/project/pyvista) (📥 27K / month):
	```
	pip install pyvista
	```
- [Conda](https://anaconda.org/conda-forge/pyvista) (📥 80K · ⏱️ 14.04.2021):
	```
	conda install -c conda-forge pyvista
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/data-validation">data-validation</a></b> (🥈27 ·  ⭐ 540) - Library for exploring and validating machine learning.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/data-validation) (👨‍💻 20 · 🔀 95 · 📥 210 · 📦 270 · 📋 120 - 25% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/tensorflow/data-validation
	```
- [PyPi](https://pypi.org/project/tensorflow-data-validation) (📥 6M / month):
	```
	pip install tensorflow-data-validation
	```
</details>
<details><summary><b><a href="https://github.com/holoviz/datashader">datashader</a></b> (🥈26 ·  ⭐ 2.5K) - Quickly and accurately render even the largest data. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/holoviz/datashader) (👨‍💻 43 · 🔀 310 · 📦 660 · 📋 460 - 25% open · ⏱️ 13.04.2021):

	```
	git clone https://github.com/holoviz/datashader
	```
- [PyPi](https://pypi.org/project/datashader) (📥 36K / month):
	```
	pip install datashader
	```
- [Conda](https://anaconda.org/conda-forge/datashader) (📥 170K · ⏱️ 13.04.2021):
	```
	conda install -c conda-forge datashader
	```
</details>
<details><summary><b><a href="https://github.com/santosjorge/cufflinks">Cufflinks</a></b> (🥈26 ·  ⭐ 2.2K) - Productivity Tools for Plotly + Pandas. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/santosjorge/cufflinks) (👨‍💻 38 · 🔀 520 · 📦 3.2K · 📋 190 - 36% open · ⏱️ 25.02.2021):

	```
	git clone https://github.com/santosjorge/cufflinks
	```
- [PyPi](https://pypi.org/project/cufflinks) (📥 100K / month):
	```
	pip install cufflinks
	```
</details>
<details><summary><b><a href="https://github.com/holoviz/holoviews">HoloViews</a></b> (🥈26 ·  ⭐ 1.9K) - With Holoviews, your data visualizes itself. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/holoviz/holoviews) (👨‍💻 100 · 🔀 310 · 📋 2.5K - 27% open · ⏱️ 21.04.2021):

	```
	git clone https://github.com/holoviz/holoviews
	```
- [PyPi](https://pypi.org/project/holoviews) (📥 90K / month):
	```
	pip install holoviews
	```
- [Conda](https://anaconda.org/conda-forge/holoviews) (📥 470K · ⏱️ 08.04.2021):
	```
	conda install -c conda-forge holoviews
	```
- [NPM](https://www.npmjs.com/package/@pyviz/jupyterlab_pyviz) (📥 5.9K / month):
	```
	npm install @pyviz/jupyterlab_pyviz
	```
</details>
<details><summary><b><a href="https://github.com/PAIR-code/facets">Facets Overview</a></b> (🥉25 ·  ⭐ 6.6K) - Visualizations for machine learning datasets. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PAIR-code/facets) (👨‍💻 28 · 🔀 800 · 📦 42 · 📋 150 - 48% open · ⏱️ 04.02.2021):

	```
	git clone https://github.com/pair-code/facets
	```
- [PyPi](https://pypi.org/project/facets-overview) (📥 120K / month):
	```
	pip install facets-overview
	```
</details>
<details><summary><b><a href="https://github.com/spotify/chartify">Chartify</a></b> (🥉25 ·  ⭐ 2.9K) - Python library that makes it easy for data scientists to create.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/spotify/chartify) (👨‍💻 21 · 🔀 260 · 📦 53 · 📋 70 - 57% open · ⏱️ 05.02.2021):

	```
	git clone https://github.com/spotify/chartify
	```
- [PyPi](https://pypi.org/project/chartify) (📥 3K / month):
	```
	pip install chartify
	```
- [Conda](https://anaconda.org/conda-forge/chartify) (📥 13K · ⏱️ 07.11.2020):
	```
	conda install -c conda-forge chartify
	```
</details>
<details><summary><b><a href="https://github.com/ContextLab/hypertools">HyperTools</a></b> (🥉25 ·  ⭐ 1.6K) - A Python toolbox for gaining geometric insights into high-dimensional.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ContextLab/hypertools) (👨‍💻 21 · 🔀 150 · 📦 120 · 📋 190 - 35% open · ⏱️ 06.01.2021):

	```
	git clone https://github.com/ContextLab/hypertools
	```
- [PyPi](https://pypi.org/project/hypertools) (📥 11K / month):
	```
	pip install hypertools
	```
</details>
<details><summary><b><a href="https://github.com/SauceCat/PDPbox">PDPbox</a></b> (🥉25 ·  ⭐ 560) - python partial dependence plot toolbox. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/SauceCat/PDPbox) (👨‍💻 7 · 🔀 88 · 📦 370 · 📋 54 - 29% open · ⏱️ 14.03.2021):

	```
	git clone https://github.com/SauceCat/PDPbox
	```
- [PyPi](https://pypi.org/project/pdpbox) (📥 79K / month):
	```
	pip install pdpbox
	```
- [Conda](https://anaconda.org/conda-forge/pdpbox) (📥 7.1K · ⏱️ 14.03.2021):
	```
	conda install -c conda-forge pdpbox
	```
</details>
<details><summary><b><a href="https://github.com/holoviz/hvplot">hvPlot</a></b> (🥉25 ·  ⭐ 380) - A high-level plotting API for pandas, dask, xarray, and networkx built on.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/holoviz/hvplot) (👨‍💻 28 · 🔀 53 · 📦 570 · 📋 350 - 34% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/holoviz/hvplot
	```
- [PyPi](https://pypi.org/project/hvplot) (📥 29K / month):
	```
	pip install hvplot
	```
- [Conda](https://anaconda.org/conda-forge/hvplot) (📥 82K · ⏱️ 04.03.2021):
	```
	conda install -c conda-forge hvplot
	```
</details>
<details><summary><b><a href="https://github.com/man-group/dtale">D-Tale</a></b> (🥉24 ·  ⭐ 2.3K) - Visualizer for pandas data structures. <code><a href="https://tldrlegal.com/search?q=LGPL-2.1">❗️LGPL-2.1</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/man-group/dtale) (👨‍💻 15 · 🔀 170 · 📦 140 · 📋 330 - 6% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/man-group/dtale
	```
- [PyPi](https://pypi.org/project/dtale) (📥 14K / month):
	```
	pip install dtale
	```
- [Conda](https://anaconda.org/conda-forge/dtale) (📥 52K · ⏱️ 27.04.2021):
	```
	conda install -c conda-forge dtale
	```
</details>
<details><summary><b><a href="https://github.com/pavlin-policar/openTSNE">openTSNE</a></b> (🥉24 ·  ⭐ 790) - Extensible, parallel implementations of t-SNE. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/pavlin-policar/openTSNE) (👨‍💻 10 · 🔀 82 · 📦 200 · 📋 85 - 4% open · ⏱️ 25.04.2021):

	```
	git clone https://github.com/pavlin-policar/openTSNE
	```
- [PyPi](https://pypi.org/project/opentsne) (📥 16K / month):
	```
	pip install opentsne
	```
- [Conda](https://anaconda.org/conda-forge/opentsne) (📥 92K · ⏱️ 26.04.2021):
	```
	conda install -c conda-forge opentsne
	```
</details>
<details><summary><b><a href="https://github.com/finos/perspective">Perspective</a></b> (🥉23 ·  ⭐ 3.3K) - Streaming pivot visualization via WebAssembly. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/finos/perspective) (👨‍💻 62 · 🔀 360 · 📦 180 · 📋 400 - 14% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/finos/perspective
	```
- [PyPi](https://pypi.org/project/perspective-python) (📥 1.8K / month):
	```
	pip install perspective-python
	```
- [NPM](https://www.npmjs.com/package/@finos/perspective-jupyterlab) (📥 2K / month):
	```
	npm install @finos/perspective-jupyterlab
	```
</details>
<details><summary><b><a href="https://github.com/pyqtgraph/pyqtgraph">PyQtGraph</a></b> (🥉23 ·  ⭐ 2.4K) - Fast data visualization and GUI tools for scientific /.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/pyqtgraph/pyqtgraph) (👨‍💻 190 · 🔀 810 · 📋 790 - 32% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/pyqtgraph/pyqtgraph
	```
- [PyPi](https://pypi.org/project/pyqtgraph) (📥 59K / month):
	```
	pip install pyqtgraph
	```
- [Conda](https://anaconda.org/conda-forge/pyqtgraph) (📥 170K · ⏱️ 07.04.2021):
	```
	conda install -c conda-forge pyqtgraph
	```
</details>
<details><summary><b><a href="https://github.com/PatrikHlobil/Pandas-Bokeh">Pandas-Bokeh</a></b> (🥉23 ·  ⭐ 660) - Bokeh Plotting Backend for Pandas and GeoPandas. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PatrikHlobil/Pandas-Bokeh) (👨‍💻 12 · 🔀 82 · 📦 160 · 📋 77 - 23% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/PatrikHlobil/Pandas-Bokeh
	```
- [PyPi](https://pypi.org/project/pandas-bokeh) (📥 9.2K / month):
	```
	pip install pandas-bokeh
	```
</details>
<details><summary><b><a href="https://github.com/marcharper/python-ternary">python-ternary</a></b> (🥉23 ·  ⭐ 410) - Ternary plotting library for python with matplotlib. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/marcharper/python-ternary) (👨‍💻 25 · 🔀 110 · 📥 14 · 📦 64 · 📋 110 - 21% open · ⏱️ 31.03.2021):

	```
	git clone https://github.com/marcharper/python-ternary
	```
- [PyPi](https://pypi.org/project/python-ternary) (📥 3.8K / month):
	```
	pip install python-ternary
	```
- [Conda](https://anaconda.org/conda-forge/python-ternary) (📥 53K · ⏱️ 17.02.2021):
	```
	conda install -c conda-forge python-ternary
	```
</details>
<details><summary><b><a href="https://github.com/DmitryUlyanov/Multicore-TSNE">Multicore-TSNE</a></b> (🥉21 ·  ⭐ 1.6K · 💤) - Parallel t-SNE implementation with Python and Torch.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/DmitryUlyanov/Multicore-TSNE) (👨‍💻 15 · 🔀 180 · 📦 220 · 📋 50 - 60% open · ⏱️ 19.08.2020):

	```
	git clone https://github.com/DmitryUlyanov/Multicore-TSNE
	```
- [PyPi](https://pypi.org/project/MulticoreTSNE) (📥 4.7K / month):
	```
	pip install MulticoreTSNE
	```
- [Conda](https://anaconda.org/conda-forge/multicore-tsne) (📥 6.8K · ⏱️ 23.04.2021):
	```
	conda install -c conda-forge multicore-tsne
	```
</details>
<details><summary><b><a href="https://github.com/fbdesignpro/sweetviz">Sweetviz</a></b> (🥉21 ·  ⭐ 1.5K) - Visualize and compare datasets, target values and associations, with one.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/fbdesignpro/sweetviz) (👨‍💻 6 · 🔀 160 · 📋 75 - 26% open · ⏱️ 01.04.2021):

	```
	git clone https://github.com/fbdesignpro/sweetviz
	```
- [PyPi](https://pypi.org/project/sweetviz) (📥 27K / month):
	```
	pip install sweetviz
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-widgets/pythreejs">pythreejs</a></b> (🥉21 ·  ⭐ 720) - A Jupyter - Three.js bridge. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/jupyter-widgets/pythreejs) (👨‍💻 27 · 🔀 150 · 📦 15 · 📋 200 - 29% open · ⏱️ 26.02.2021):

	```
	git clone https://github.com/jupyter-widgets/pythreejs
	```
- [PyPi](https://pypi.org/project/pythreejs) (📥 23K / month):
	```
	pip install pythreejs
	```
- [Conda](https://anaconda.org/conda-forge/pythreejs) (📥 290K · ⏱️ 02.03.2021):
	```
	conda install -c conda-forge pythreejs
	```
- [NPM](https://www.npmjs.com/package/jupyter-threejs) (📥 9.8K / month):
	```
	npm install jupyter-threejs
	```
</details>
<details><summary><b><a href="https://github.com/adamerose/PandasGUI">PandasGUI</a></b> (🥉20 ·  ⭐ 2.2K) - A GUI for Pandas DataFrames. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/adamerose/PandasGUI) (👨‍💻 8 · 🔀 120 · 📦 62 · 📋 100 - 25% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/adamerose/pandasgui
	```
- [PyPi](https://pypi.org/project/pandasgui) (📥 3K / month):
	```
	pip install pandasgui
	```
</details>
<details><summary><b><a href="https://github.com/t-makaro/animatplot">animatplot</a></b> (🥉19 ·  ⭐ 360) - A python package for animating plots build on matplotlib. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/t-makaro/animatplot) (👨‍💻 7 · 🔀 32 · 📦 14 · 📋 29 - 44% open · ⏱️ 05.10.2020):

	```
	git clone https://github.com/t-makaro/animatplot
	```
- [PyPi](https://pypi.org/project/animatplot) (📥 740 / month):
	```
	pip install animatplot
	```
- [Conda](https://anaconda.org/conda-forge/animatplot) (📥 5.7K · ⏱️ 06.10.2020):
	```
	conda install -c conda-forge animatplot
	```
</details>
<details><summary><b><a href="https://github.com/sbebo/joypy">joypy</a></b> (🥉19 ·  ⭐ 330) - Joyplots in Python with matplotlib & pandas. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/sbebo/joypy) (👨‍💻 5 · 🔀 33 · 📦 74 · 📋 41 - 12% open · ⏱️ 02.04.2021):

	```
	git clone https://github.com/sbebo/joypy
	```
- [PyPi](https://pypi.org/project/joypy) (📥 7.6K / month):
	```
	pip install joypy
	```
- [Conda](https://anaconda.org/conda-forge/joypy) (📥 9.2K · ⏱️ 28.12.2020):
	```
	conda install -c conda-forge joypy
	```
</details>
<details><summary><b><a href="https://github.com/beringresearch/ivis">ivis</a></b> (🥉19 ·  ⭐ 230) - Dimensionality reduction in very large datasets using Siamese.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/beringresearch/ivis) (👨‍💻 8 · 🔀 23 · 📦 15 · 📋 44 - 4% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/beringresearch/ivis
	```
- [PyPi](https://pypi.org/project/ivis) (📥 940 / month):
	```
	pip install ivis
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/hiplot">HiPlot</a></b> (🥉18 ·  ⭐ 2.1K) - HiPlot makes understanding high dimensional data easy. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebookresearch/hiplot) (👨‍💻 6 · 🔀 93 · 📦 2 · 📋 62 - 12% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/facebookresearch/hiplot
	```
- [PyPi](https://pypi.org/project/hiplot) (📥 7.8K / month):
	```
	pip install hiplot
	```
- [Conda](https://anaconda.org/conda-forge/hiplot) (📥 53K · ⏱️ 24.03.2021):
	```
	conda install -c conda-forge hiplot
	```
</details>
<details><summary><b><a href="https://github.com/JetBrains/lets-plot">lets-plot</a></b> (🥉18 ·  ⭐ 580) - An open-source plotting library for statistical data. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/JetBrains/lets-plot) (👨‍💻 15 · 🔀 20 · 📥 55 · 📦 7 · 📋 160 - 39% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/JetBrains/lets-plot
	```
- [PyPi](https://pypi.org/project/lets-plot) (📥 5.3K / month):
	```
	pip install lets-plot
	```
</details>
<details><summary><b><a href="https://github.com/gyli/PyWaffle">PyWaffle</a></b> (🥉18 ·  ⭐ 420 · 💤) - Make Waffle Charts in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/gyli/PyWaffle) (👨‍💻 6 · 🔀 66 · 📦 49 · 📋 12 - 16% open · ⏱️ 26.07.2020):

	```
	git clone https://github.com/gyli/PyWaffle
	```
- [PyPi](https://pypi.org/project/pywaffle) (📥 1.8K / month):
	```
	pip install pywaffle
	```
</details>
<details><summary><b><a href="https://github.com/vega/ipyvega">vega</a></b> (🥉18 ·  ⭐ 300) - IPython/Jupyter notebook module for Vega and Vega-Lite. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/vega/ipyvega) (👨‍💻 9 · 🔀 41 · 📋 87 - 9% open · ⏱️ 02.04.2021):

	```
	git clone https://github.com/vega/ipyvega
	```
- [PyPi](https://pypi.org/project/vega) (📥 19K / month):
	```
	pip install vega
	```
- [Conda](https://anaconda.org/conda-forge/vega) (📥 410K · ⏱️ 10.12.2020):
	```
	conda install -c conda-forge vega
	```
</details>
<details><summary><b><a href="https://github.com/nicolaskruchten/jupyter_pivottablejs">pivottablejs</a></b> (🥉17 ·  ⭐ 430 · 💀) - Dragndrop Pivot Tables and Charts for Jupyter/IPython.. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/nicolaskruchten/jupyter_pivottablejs) (👨‍💻 3 · 🔀 58 · 📦 160 · 📋 53 - 30% open · ⏱️ 04.12.2018):

	```
	git clone https://github.com/nicolaskruchten/jupyter_pivottablejs
	```
- [PyPi](https://pypi.org/project/pivottablejs) (📥 7.9K / month):
	```
	pip install pivottablejs
	```
</details>
<details><summary><b><a href="https://github.com/altair-viz/pdvega">pdvega</a></b> (🥉16 ·  ⭐ 340 · 💀) - Interactive plotting for Pandas using Vega-Lite. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/altair-viz/pdvega) (👨‍💻 9 · 🔀 29 · 📦 48 · 📋 26 - 61% open · ⏱️ 29.03.2019):

	```
	git clone https://github.com/altair-viz/pdvega
	```
- [PyPi](https://pypi.org/project/pdvega) (📥 150 / month):
	```
	pip install pdvega
	```
</details>
<details><summary><b><a href="https://github.com/AutoViML/AutoViz">AutoViz</a></b> (🥉16 ·  ⭐ 340) - Automatically Visualize any dataset, any size with a single line of.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/AutoViML/AutoViz) (👨‍💻 10 · 🔀 58 · 📦 36 · 📋 23 - 13% open · ⏱️ 21.12.2020):

	```
	git clone https://github.com/AutoViML/AutoViz
	```
- [PyPi](https://pypi.org/project/autoviz) (📥 3.5K / month):
	```
	pip install autoviz
	```
</details>
<details><summary><b><a href="https://github.com/voxel51/fiftyone">FiftyOne</a></b> (🥉15 ·  ⭐ 260) - Visualize, create, and debug image and video datasets.. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/voxel51/fiftyone) (👨‍💻 11 · 🔀 25 · 📋 380 - 32% open · ⏱️ 24.04.2021):

	```
	git clone https://github.com/voxel51/fiftyone
	```
- [PyPi](https://pypi.org/project/fiftyone) (📥 1.6K / month):
	```
	pip install fiftyone
	```
</details>
<details><summary><b><a href="https://github.com/data-describe/data-describe">data-describe</a></b> (🥉13 ·  ⭐ 280) - datadescribe: Pythonic EDA Accelerator for Data Science. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/data-describe/data-describe) (👨‍💻 14 · 🔀 14 · 📋 240 - 28% open · ⏱️ 02.03.2021):

	```
	git clone https://github.com/data-describe/data-describe
	```
- [PyPi](https://pypi.org/project/data-describe) (📥 320 / month):
	```
	pip install data-describe
	```
</details>
<details><summary><b><a href="https://github.com/Zsailer/nx_altair">nx-altair</a></b> (🥉12 ·  ⭐ 160 · 💤) - Draw interactive NetworkX graphs with Altair. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/Zsailer/nx_altair) (👨‍💻 3 · 🔀 20 · 📋 9 - 55% open · ⏱️ 02.06.2020):

	```
	git clone https://github.com/Zsailer/nx_altair
	```
- [PyPi](https://pypi.org/project/nx-altair) (📥 450 / month):
	```
	pip install nx-altair
	```
</details>
<details><summary><b><a href="https://github.com/biovault/nptsne">nptsne</a></b> (🥉12 ·  ⭐ 25) - nptsne is a numpy compatible python binary package that offers a number.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/biovault/nptsne) (👨‍💻 3 · 🔀 2 · 📦 2 · 📋 11 - 54% open · ⏱️ 03.02.2021):

	```
	git clone https://github.com/biovault/nptsne
	```
- [PyPi](https://pypi.org/project/nptsne) (📥 210 / month):
	```
	pip install nptsne
	```
</details>
<br>

## Text Data & NLP

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for processing, cleaning, manipulating, and analyzing text data as well as libraries for NLP tasks such as language detection, fuzzy matching, classification, seq2seq learning, conversational AI, keyword extraction, and translation._

<details><summary><b><a href="https://github.com/explosion/spaCy">spaCy</a></b> (🥇37 ·  ⭐ 20K) - Industrial-strength Natural Language Processing (NLP) in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/explosion/spaCy) (👨‍💻 580 · 🔀 3.3K · 📥 3K · 📦 24K · 📋 4.6K - 1% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/explosion/spaCy
	```
- [PyPi](https://pypi.org/project/spacy) (📥 2M / month):
	```
	pip install spacy
	```
- [Conda](https://anaconda.org/conda-forge/spacy) (📥 1.8M · ⏱️ 24.04.2021):
	```
	conda install -c conda-forge spacy
	```
</details>
<details><summary><b><a href="https://github.com/huggingface/transformers">transformers</a></b> (🥇36 ·  ⭐ 45K) - Transformers: State-of-the-art Natural Language.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/huggingface/transformers) (👨‍💻 860 · 🔀 10K · 📥 1.3K · 📦 10K · 📋 6.6K - 5% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/huggingface/transformers
	```
- [PyPi](https://pypi.org/project/transformers) (📥 1.9M / month):
	```
	pip install transformers
	```
- [Conda](https://anaconda.org/conda-forge/transformers) (📥 37K · ⏱️ 14.04.2021):
	```
	conda install -c conda-forge transformers
	```
</details>
<details><summary><b><a href="https://github.com/RaRe-Technologies/gensim">gensim</a></b> (🥇36 ·  ⭐ 12K) - Topic Modelling for Humans. <code><a href="https://tldrlegal.com/search?q=LGPL-2.1">❗️LGPL-2.1</a></code></summary>

- [GitHub](https://github.com/RaRe-Technologies/gensim) (👨‍💻 390 · 🔀 3.8K · 📥 3.3K · 📦 23K · 📋 1.6K - 20% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/RaRe-Technologies/gensim
	```
- [PyPi](https://pypi.org/project/gensim) (📥 8.4M / month):
	```
	pip install gensim
	```
- [Conda](https://anaconda.org/conda-forge/gensim) (📥 640K · ⏱️ 02.04.2021):
	```
	conda install -c conda-forge gensim
	```
</details>
<details><summary><b><a href="https://github.com/nltk/nltk">nltk</a></b> (🥇33 ·  ⭐ 9.8K) - Suite of libraries and programs for symbolic and statistical natural.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/nltk/nltk) (👨‍💻 400 · 🔀 2.3K · 📦 98K · 📋 1.5K - 15% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/nltk/nltk
	```
- [PyPi](https://pypi.org/project/nltk) (📥 13M / month):
	```
	pip install nltk
	```
- [Conda](https://anaconda.org/conda-forge/nltk) (📥 680K · ⏱️ 20.04.2021):
	```
	conda install -c conda-forge nltk
	```
</details>
<details><summary><b><a href="https://github.com/allenai/allennlp">AllenNLP</a></b> (🥇32 ·  ⭐ 9.9K) - An open-source NLP research library, built on PyTorch. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/allenai/allennlp) (👨‍💻 240 · 🔀 2K · 📥 37 · 📦 1.6K · 📋 2.3K - 3% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/allenai/allennlp
	```
- [PyPi](https://pypi.org/project/allennlp) (📥 39K / month):
	```
	pip install allennlp
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/fairseq">fairseq</a></b> (🥇31 ·  ⭐ 12K) - Facebook AI Research Sequence-to-Sequence Toolkit written in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/fairseq) (👨‍💻 320 · 🔀 3K · 📥 120 · 📦 360 · 📋 2.6K - 28% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/pytorch/fairseq
	```
- [PyPi](https://pypi.org/project/fairseq) (📥 25K / month):
	```
	pip install fairseq
	```
</details>
<details><summary><b><a href="https://github.com/google/sentencepiece">sentencepiece</a></b> (🥇31 ·  ⭐ 5K) - Unsupervised text tokenizer for Neural Network-based text.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google/sentencepiece) (👨‍💻 52 · 🔀 660 · 📥 13K · 📦 7.2K · 📋 440 - 7% open · ⏱️ 20.04.2021):

	```
	git clone https://github.com/google/sentencepiece
	```
- [PyPi](https://pypi.org/project/sentencepiece) (📥 2.1M / month):
	```
	pip install sentencepiece
	```
- [Conda](https://anaconda.org/conda-forge/sentencepiece) (📥 49K · ⏱️ 09.02.2021):
	```
	conda install -c conda-forge sentencepiece
	```
</details>
<details><summary><b><a href="https://github.com/gunthercox/ChatterBot">ChatterBot</a></b> (🥇30 ·  ⭐ 11K · 💤) - ChatterBot is a machine learning, conversational dialog engine.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/gunthercox/ChatterBot) (👨‍💻 100 · 🔀 3.7K · 📦 3.4K · 📋 1.5K - 15% open · ⏱️ 20.08.2020):

	```
	git clone https://github.com/gunthercox/ChatterBot
	```
- [PyPi](https://pypi.org/project/chatterbot) (📥 22K / month):
	```
	pip install chatterbot
	```
</details>
<details><summary><b><a href="https://github.com/seatgeek/fuzzywuzzy">fuzzywuzzy</a></b> (🥇30 ·  ⭐ 8K) - Fuzzy String Matching in Python. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/seatgeek/fuzzywuzzy) (👨‍💻 68 · 🔀 820 · 📦 8.6K · 📋 170 - 42% open · ⏱️ 20.02.2021):

	```
	git clone https://github.com/seatgeek/fuzzywuzzy
	```
- [PyPi](https://pypi.org/project/fuzzywuzzy) (📥 4.9M / month):
	```
	pip install fuzzywuzzy
	```
- [Conda](https://anaconda.org/conda-forge/fuzzywuzzy) (📥 290K · ⏱️ 18.11.2020):
	```
	conda install -c conda-forge fuzzywuzzy
	```
</details>
<details><summary><b><a href="https://github.com/sloria/TextBlob">TextBlob</a></b> (🥇30 ·  ⭐ 7.6K) - Simple, Pythonic, text processing--Sentiment analysis, part-of-speech.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/sloria/TextBlob) (👨‍💻 34 · 🔀 970 · 📥 90 · 📦 12K · 📋 230 - 34% open · ⏱️ 16.04.2021):

	```
	git clone https://github.com/sloria/TextBlob
	```
- [PyPi](https://pypi.org/project/textblob) (📥 470K / month):
	```
	pip install textblob
	```
- [Conda](https://anaconda.org/conda-forge/textblob) (📥 120K · ⏱️ 24.02.2019):
	```
	conda install -c conda-forge textblob
	```
</details>
<details><summary><b><a href="https://github.com/UKPLab/sentence-transformers">sentence-transformers</a></b> (🥇30 ·  ⭐ 4.9K) - Sentence Embeddings with BERT & XLNet. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/UKPLab/sentence-transformers) (👨‍💻 45 · 🔀 900 · 📦 930 · 📋 820 - 47% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/UKPLab/sentence-transformers
	```
- [PyPi](https://pypi.org/project/sentence-transformers) (📥 1.1M / month):
	```
	pip install sentence-transformers
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/text">torchtext</a></b> (🥇30 ·  ⭐ 2.7K) - Data loaders and abstractions for text and NLP. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/text) (👨‍💻 110 · 🔀 600 · 📦 4.3K · 📋 550 - 41% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/pytorch/text
	```
- [PyPi](https://pypi.org/project/torchtext) (📥 150K / month):
	```
	pip install torchtext
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/fastText">fastText</a></b> (🥈29 ·  ⭐ 23K · 💤) - Library for fast text representation and classification. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebookresearch/fastText) (👨‍💻 58 · 🔀 4.2K · 📦 1.7K · 📋 960 - 38% open · ⏱️ 18.07.2020):

	```
	git clone https://github.com/facebookresearch/fastText
	```
- [PyPi](https://pypi.org/project/fasttext) (📥 320K / month):
	```
	pip install fasttext
	```
- [Conda](https://anaconda.org/conda-forge/fasttext) (📥 19K · ⏱️ 12.10.2020):
	```
	conda install -c conda-forge fasttext
	```
</details>
<details><summary><b><a href="https://github.com/flairNLP/flair">flair</a></b> (🥈29 ·  ⭐ 10K) - A very simple framework for state-of-the-art Natural Language.. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/flairNLP/flair) (👨‍💻 200 · 🔀 1.3K · 📦 720 · 📋 1.5K - 5% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/flairNLP/flair
	```
- [PyPi](https://pypi.org/project/flair) (📥 60K / month):
	```
	pip install flair
	```
</details>
<details><summary><b><a href="https://github.com/snowballstem/snowball">snowballstemmer</a></b> (🥈29 ·  ⭐ 490) - Snowball compiler and stemming algorithms. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/snowballstem/snowball) (👨‍💻 26 · 🔀 130 · 📦 48K · 📋 54 - 22% open · ⏱️ 11.04.2021):

	```
	git clone https://github.com/snowballstem/snowball
	```
- [PyPi](https://pypi.org/project/snowballstemmer) (📥 5.6M / month):
	```
	pip install snowballstemmer
	```
- [Conda](https://anaconda.org/conda-forge/snowballstemmer) (📥 2.4M · ⏱️ 21.01.2021):
	```
	conda install -c conda-forge snowballstemmer
	```
</details>
<details><summary><b><a href="https://github.com/OpenNMT/OpenNMT-py">OpenNMT</a></b> (🥈28 ·  ⭐ 5K) - Open Source Neural Machine Translation in PyTorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/OpenNMT/OpenNMT-py) (👨‍💻 170 · 🔀 1.7K · 📦 84 · 📋 1.2K - 6% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/OpenNMT/OpenNMT-py
	```
- [PyPi](https://pypi.org/project/OpenNMT-py) (📥 5.2K / month):
	```
	pip install OpenNMT-py
	```
</details>
<details><summary><b><a href="https://github.com/deepmipt/DeepPavlov">DeepPavlov</a></b> (🥈27 ·  ⭐ 5.2K) - An open source library for deep learning end-to-end dialog.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deepmipt/DeepPavlov) (👨‍💻 61 · 🔀 930 · 📦 190 · 📋 560 - 18% open · ⏱️ 03.04.2021):

	```
	git clone https://github.com/deepmipt/DeepPavlov
	```
- [PyPi](https://pypi.org/project/deeppavlov) (📥 9.1K / month):
	```
	pip install deeppavlov
	```
</details>
<details><summary><b><a href="https://github.com/huggingface/tokenizers">Tokenizers</a></b> (🥈27 ·  ⭐ 4.5K) - Fast State-of-the-Art Tokenizers optimized for Research and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/huggingface/tokenizers) (👨‍💻 40 · 🔀 330 · 📦 32 · 📋 420 - 23% open · ⏱️ 21.04.2021):

	```
	git clone https://github.com/huggingface/tokenizers
	```
- [PyPi](https://pypi.org/project/tokenizers) (📥 2.3M / month):
	```
	pip install tokenizers
	```
- [Conda](https://anaconda.org/conda-forge/tokenizers) (📥 47K · ⏱️ 10.03.2021):
	```
	conda install -c conda-forge tokenizers
	```
</details>
<details><summary><b><a href="https://github.com/LuminosoInsight/python-ftfy">ftfy</a></b> (🥈27 ·  ⭐ 2.9K) - Fixes mojibake and other glitches in Unicode text, after the fact. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/LuminosoInsight/python-ftfy) (👨‍💻 17 · 🔀 98 · 📦 3.1K · 📋 110 - 11% open · ⏱️ 16.04.2021):

	```
	git clone https://github.com/LuminosoInsight/python-ftfy
	```
- [PyPi](https://pypi.org/project/ftfy) (📥 820K / month):
	```
	pip install ftfy
	```
- [Conda](https://anaconda.org/conda-forge/ftfy) (📥 100K · ⏱️ 19.04.2021):
	```
	conda install -c conda-forge ftfy
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/ParlAI">ParlAI</a></b> (🥈26 ·  ⭐ 7.1K) - A framework for training and evaluating AI models on a variety of.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/ParlAI) (👨‍💻 150 · 🔀 1.4K · 📦 21 · 📋 970 - 8% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/facebookresearch/ParlAI
	```
- [PyPi](https://pypi.org/project/parlai) (📥 2.6K / month):
	```
	pip install parlai
	```
</details>
<details><summary><b><a href="https://github.com/dmlc/gluon-nlp">GluonNLP</a></b> (🥈26 ·  ⭐ 2.3K) - Toolkit that enables easy text preprocessing, datasets loading.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/dmlc/gluon-nlp) (👨‍💻 79 · 🔀 480 · 📦 460 · 📋 520 - 44% open · ⏱️ 22.04.2021):

	```
	git clone https://github.com/dmlc/gluon-nlp
	```
- [PyPi](https://pypi.org/project/gluonnlp) (📥 46K / month):
	```
	pip install gluonnlp
	```
</details>
<details><summary><b><a href="https://github.com/JohnSnowLabs/spark-nlp">spark-nlp</a></b> (🥈26 ·  ⭐ 2.1K) - State of the Art Natural Language Processing. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/JohnSnowLabs/spark-nlp) (👨‍💻 84 · 🔀 420 · 📋 460 - 15% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/JohnSnowLabs/spark-nlp
	```
- [PyPi](https://pypi.org/project/spark-nlp) (📥 690K / month):
	```
	pip install spark-nlp
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/text">TensorFlow Text</a></b> (🥈26 ·  ⭐ 720) - Making text a first-class citizen in TensorFlow. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/text) (👨‍💻 37 · 🔀 84 · 📦 620 · 📋 110 - 15% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/tensorflow/text
	```
- [PyPi](https://pypi.org/project/tensorflow-text) (📥 360K / month):
	```
	pip install tensorflow-text
	```
</details>
<details><summary><b><a href="https://github.com/RasaHQ/rasa">Rasa</a></b> (🥈25 ·  ⭐ 11K) - Open source machine learning framework to automate text- and voice-.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/RasaHQ/rasa) (👨‍💻 480 · 🔀 3.3K · 📋 5.3K - 10% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/RasaHQ/rasa
	```
- [PyPi](https://pypi.org/project/rasa) (📥 170K / month):
	```
	pip install rasa
	```
</details>
<details><summary><b><a href="https://github.com/dedupeio/dedupe">Dedupe</a></b> (🥈25 ·  ⭐ 3K) - A python library for accurate and scalable fuzzy matching, record.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/dedupeio/dedupe) (👨‍💻 56 · 🔀 410 · 📦 180 · 📋 640 - 8% open · ⏱️ 17.04.2021):

	```
	git clone https://github.com/dedupeio/dedupe
	```
- [PyPi](https://pypi.org/project/dedupe) (📥 89K / month):
	```
	pip install dedupe
	```
</details>
<details><summary><b><a href="https://github.com/fastnlp/fastNLP">fastNLP</a></b> (🥈25 ·  ⭐ 2.1K) - fastNLP: A Modularized and Extensible NLP Framework. Currently still.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/fastnlp/fastNLP) (👨‍💻 50 · 🔀 360 · 📥 54 · 📦 31 · 📋 150 - 13% open · ⏱️ 12.04.2021):

	```
	git clone https://github.com/fastnlp/fastNLP
	```
- [PyPi](https://pypi.org/project/fastnlp) (📥 1.1K / month):
	```
	pip install fastnlp
	```
</details>
<details><summary><b><a href="https://github.com/life4/textdistance">TextDistance</a></b> (🥈25 ·  ⭐ 2K) - Compute distance between sequences. 30+ algorithms, pure python.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/life4/textdistance) (👨‍💻 9 · 🔀 160 · 📥 100 · 📦 520 · ⏱️ 29.01.2021):

	```
	git clone https://github.com/life4/textdistance
	```
- [PyPi](https://pypi.org/project/textdistance) (📥 220K / month):
	```
	pip install textdistance
	```
- [Conda](https://anaconda.org/conda-forge/textdistance) (📥 34K · ⏱️ 29.01.2021):
	```
	conda install -c conda-forge textdistance
	```
</details>
<details><summary><b><a href="https://github.com/deepset-ai/haystack">haystack</a></b> (🥈25 ·  ⭐ 1.7K) - End-to-end Python framework for building natural language search.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/deepset-ai/haystack) (👨‍💻 43 · 🔀 320 · 📦 46 · 📋 570 - 14% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/deepset-ai/haystack
	```
- [PyPi](https://pypi.org/project/haystack) (📥 1.5K / month):
	```
	pip install haystack
	```
</details>
<details><summary><b><a href="https://github.com/jamesturk/jellyfish">jellyfish</a></b> (🥈25 ·  ⭐ 1.4K) - a python library for doing approximate and phonetic matching of.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/jamesturk/jellyfish) (👨‍💻 22 · 🔀 130 · 📦 2.3K · 📋 99 - 10% open · ⏱️ 21.04.2021):

	```
	git clone https://github.com/jamesturk/jellyfish
	```
- [PyPi](https://pypi.org/project/jellyfish) (📥 1.4M / month):
	```
	pip install jellyfish
	```
- [Conda](https://anaconda.org/conda-forge/jellyfish) (📥 120K · ⏱️ 08.01.2021):
	```
	conda install -c conda-forge jellyfish
	```
</details>
<details><summary><b><a href="https://github.com/cltk/cltk">CLTK</a></b> (🥈25 ·  ⭐ 660) - The Classical Language Toolkit. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/cltk/cltk) (👨‍💻 110 · 🔀 300 · 📥 22 · 📦 160 · 📋 490 - 24% open · ⏱️ 13.04.2021):

	```
	git clone https://github.com/cltk/cltk
	```
- [PyPi](https://pypi.org/project/cltk) (📥 3.6K / month):
	```
	pip install cltk
	```
</details>
<details><summary><b><a href="https://github.com/cjhutto/vaderSentiment">vaderSentiment</a></b> (🥈24 ·  ⭐ 2.9K) - VADER Sentiment Analysis. VADER (Valence Aware Dictionary and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/cjhutto/vaderSentiment) (👨‍💻 10 · 🔀 760 · 📦 2.6K · 📋 100 - 26% open · ⏱️ 15.03.2021):

	```
	git clone https://github.com/cjhutto/vaderSentiment
	```
- [PyPi](https://pypi.org/project/vadersentiment) (📥 140K / month):
	```
	pip install vadersentiment
	```
</details>
<details><summary><b><a href="https://github.com/miso-belica/sumy">Sumy</a></b> (🥈24 ·  ⭐ 2.6K) - Module for automatic summarization of text documents and HTML pages. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/miso-belica/sumy) (👨‍💻 20 · 🔀 450 · 📦 750 · 📋 90 - 13% open · ⏱️ 21.11.2020):

	```
	git clone https://github.com/miso-belica/sumy
	```
- [PyPi](https://pypi.org/project/sumy) (📥 19K / month):
	```
	pip install sumy
	```
</details>
<details><summary><b><a href="https://github.com/PetrochukM/PyTorch-NLP">pytorch-nlp</a></b> (🥈24 ·  ⭐ 1.9K) - Basic Utilities for PyTorch Natural Language Processing (NLP). <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PetrochukM/PyTorch-NLP) (👨‍💻 17 · 🔀 220 · 📦 200 · 📋 61 - 19% open · ⏱️ 26.01.2021):

	```
	git clone https://github.com/PetrochukM/PyTorch-NLP
	```
- [PyPi](https://pypi.org/project/pytorch-nlp) (📥 6.4K / month):
	```
	pip install pytorch-nlp
	```
</details>
<details><summary><b><a href="https://github.com/aboSamoor/polyglot">polyglot</a></b> (🥈24 ·  ⭐ 1.8K · 💤) - Multilingual text (NLP) processing toolkit. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/aboSamoor/polyglot) (👨‍💻 26 · 🔀 290 · 📦 480 · 📋 190 - 67% open · ⏱️ 22.09.2020):

	```
	git clone https://github.com/aboSamoor/polyglot
	```
- [PyPi](https://pypi.org/project/polyglot) (📥 77K / month):
	```
	pip install polyglot
	```
</details>
<details><summary><b><a href="https://github.com/explosion/sense2vec">sense2vec</a></b> (🥈24 ·  ⭐ 1.2K) - Contextually-keyed word vectors. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/explosion/sense2vec) (👨‍💻 15 · 🔀 200 · 📥 15K · 📦 62 · 📋 97 - 14% open · ⏱️ 18.04.2021):

	```
	git clone https://github.com/explosion/sense2vec
	```
- [PyPi](https://pypi.org/project/sense2vec) (📥 5.4K / month):
	```
	pip install sense2vec
	```
- [Conda](https://anaconda.org/conda-forge/sense2vec) (📥 18K · ⏱️ 16.03.2020):
	```
	conda install -c conda-forge sense2vec
	```
</details>
<details><summary><b><a href="https://github.com/explosion/spacy-transformers">spacy-transformers</a></b> (🥈24 ·  ⭐ 940) - Use pretrained transformers like BERT, XLNet and GPT-2.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>spacy</code></summary>

- [GitHub](https://github.com/explosion/spacy-transformers) (👨‍💻 15 · 🔀 110 · 📦 130 · ⏱️ 20.04.2021):

	```
	git clone https://github.com/explosion/spacy-transformers
	```
- [PyPi](https://pypi.org/project/spacy-transformers) (📥 32K / month):
	```
	pip install spacy-transformers
	```
</details>
<details><summary><b><a href="https://github.com/WojciechMula/pyahocorasick">pyahocorasick</a></b> (🥈24 ·  ⭐ 600) - Python module (C extension and plain python) implementing Aho-.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/WojciechMula/pyahocorasick) (👨‍💻 21 · 🔀 86 · 📦 570 · 📋 100 - 32% open · ⏱️ 27.03.2021):

	```
	git clone https://github.com/WojciechMula/pyahocorasick
	```
- [PyPi](https://pypi.org/project/pyahocorasick) (📥 210K / month):
	```
	pip install pyahocorasick
	```
- [Conda](https://anaconda.org/conda-forge/pyahocorasick) (📥 120K · ⏱️ 13.10.2020):
	```
	conda install -c conda-forge pyahocorasick
	```
</details>
<details><summary><b><a href="https://github.com/Ciphey/Ciphey">Ciphey</a></b> (🥉23 ·  ⭐ 6.7K) - Automatically decrypt encryptions without knowing the key or cipher,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Ciphey/Ciphey) (👨‍💻 40 · 🔀 370 · 📋 230 - 17% open · ⏱️ 13.04.2021):

	```
	git clone https://github.com/Ciphey/Ciphey
	```
- [PyPi](https://pypi.org/project/ciphey) (📥 6.4K / month):
	```
	pip install ciphey
	```
- [Docker Hub](https://hub.docker.com/r/remnux/ciphey) (📥 9.2K · ⭐ 3 · ⏱️ 17.04.2021):
	```
	docker pull remnux/ciphey
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/pytext">PyText</a></b> (🥉23 ·  ⭐ 6.2K) - A natural language modeling framework based on PyTorch. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/pytext) (👨‍💻 180 · 🔀 780 · 📥 220 · 📦 75 · 📋 130 - 42% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/facebookresearch/pytext
	```
- [PyPi](https://pypi.org/project/pytext-nlp) (📥 660 / month):
	```
	pip install pytext-nlp
	```
</details>
<details><summary><b><a href="https://github.com/stanfordnlp/stanza">stanza</a></b> (🥉23 ·  ⭐ 5.4K) - Official Stanford NLP Python Library for Many Human Languages. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/stanfordnlp/stanza) (👨‍💻 32 · 🔀 670 · 📦 440 · 📋 490 - 11% open · ⏱️ 10.02.2021):

	```
	git clone https://github.com/stanfordnlp/stanza
	```
- [PyPi](https://pypi.org/project/stanza) (📥 41K / month):
	```
	pip install stanza
	```
- [Conda](https://anaconda.org/stanfordnlp/stanza) (📥 3.6K · ⏱️ 27.01.2021):
	```
	conda install -c stanfordnlp stanza
	```
</details>
<details><summary><b><a href="https://github.com/google-research/text-to-text-transfer-transformer">T5</a></b> (🥉23 ·  ⭐ 3.3K) - Code for the paper Exploring the Limits of Transfer Learning with a.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/google-research/text-to-text-transfer-transformer) (👨‍💻 37 · 🔀 450 · 📦 33 · 📋 350 - 8% open · ⏱️ 23.04.2021):

	```
	git clone https://github.com/google-research/text-to-text-transfer-transformer
	```
- [PyPi](https://pypi.org/project/t5) (📥 11K / month):
	```
	pip install t5
	```
</details>
<details><summary><b><a href="https://github.com/huggingface/neuralcoref">neuralcoref</a></b> (🥉23 ·  ⭐ 2.3K) - Fast Coreference Resolution in spaCy with Neural Networks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/huggingface/neuralcoref) (👨‍💻 20 · 🔀 400 · 📥 200 · 📦 330 · 📋 270 - 17% open · ⏱️ 24.02.2021):

	```
	git clone https://github.com/huggingface/neuralcoref
	```
- [PyPi](https://pypi.org/project/neuralcoref) (📥 6.8K / month):
	```
	pip install neuralcoref
	```
- [Conda](https://anaconda.org/conda-forge/neuralcoref) (📥 7.6K · ⏱️ 21.02.2020):
	```
	conda install -c conda-forge neuralcoref
	```
</details>
<details><summary><b><a href="https://github.com/chartbeat-labs/textacy">textacy</a></b> (🥉23 ·  ⭐ 1.7K) - NLP, before and after spaCy. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/chartbeat-labs/textacy) (👨‍💻 30 · 🔀 220 · 📋 230 - 12% open · ⏱️ 23.04.2021):

	```
	git clone https://github.com/chartbeat-labs/textacy
	```
- [PyPi](https://pypi.org/project/textacy) (📥 210K / month):
	```
	pip install textacy
	```
- [Conda](https://anaconda.org/conda-forge/textacy) (📥 85K · ⏱️ 13.04.2021):
	```
	conda install -c conda-forge textacy
	```
</details>
<details><summary><b><a href="https://github.com/DerwenAI/pytextrank">PyTextRank</a></b> (🥉23 ·  ⭐ 1.5K) - Python implementation of TextRank for phrase extraction and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/DerwenAI/pytextrank) (👨‍💻 13 · 🔀 280 · 📦 140 · 📋 62 - 22% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/DerwenAI/pytextrank
	```
- [PyPi](https://pypi.org/project/pytextrank) (📥 11K / month):
	```
	pip install pytextrank
	```
</details>
<details><summary><b><a href="https://github.com/nipunsadvilkar/pySBD">pySBD</a></b> (🥉23 ·  ⭐ 310) - pySBD (Python Sentence Boundary Disambiguation) is a rule-based sentence.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nipunsadvilkar/pySBD) (👨‍💻 6 · 🔀 29 · 📦 130 · 📋 55 - 12% open · ⏱️ 11.02.2021):

	```
	git clone https://github.com/nipunsadvilkar/pySBD
	```
- [PyPi](https://pypi.org/project/pysbd) (📥 24K / month):
	```
	pip install pysbd
	```
</details>
<details><summary><b><a href="https://github.com/vi3k6i5/flashtext">flashtext</a></b> (🥉22 ·  ⭐ 4.7K · 💤) - Extract Keywords from sentence or Replace keywords in sentences. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/vi3k6i5/flashtext) (👨‍💻 8 · 🔀 520 · 📦 430 · 📋 92 - 46% open · ⏱️ 03.05.2020):

	```
	git clone https://github.com/vi3k6i5/flashtext
	```
- [PyPi](https://pypi.org/project/flashtext) (📥 320K / month):
	```
	pip install flashtext
	```
</details>
<details><summary><b><a href="https://github.com/minimaxir/textgenrnn">textgenrnn</a></b> (🥉22 ·  ⭐ 4.4K · 💤) - Easily train your own text-generating neural network.. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/minimaxir/textgenrnn) (👨‍💻 19 · 🔀 670 · 📥 500 · 📦 810 · 📋 190 - 56% open · ⏱️ 14.07.2020):

	```
	git clone https://github.com/minimaxir/textgenrnn
	```
- [PyPi](https://pypi.org/project/textgenrnn) (📥 10K / month):
	```
	pip install textgenrnn
	```
</details>
<details><summary><b><a href="https://github.com/saffsd/langid.py">langid</a></b> (🥉22 ·  ⭐ 1.8K · 💀) - Stand-alone language identification system. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/saffsd/langid.py) (👨‍💻 9 · 🔀 270 · 📦 670 · 📋 70 - 35% open · ⏱️ 15.07.2017):

	```
	git clone https://github.com/saffsd/langid.py
	```
- [PyPi](https://pypi.org/project/langid) (📥 740K / month):
	```
	pip install langid
	```
</details>
<details><summary><b><a href="https://github.com/JasonKessler/scattertext">scattertext</a></b> (🥉22 ·  ⭐ 1.6K) - Beautiful visualizations of how language differs among document.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/JasonKessler/scattertext) (👨‍💻 11 · 🔀 220 · 📦 180 · 📋 78 - 20% open · ⏱️ 08.03.2021):

	```
	git clone https://github.com/JasonKessler/scattertext
	```
- [PyPi](https://pypi.org/project/scattertext) (📥 4.9K / month):
	```
	pip install scattertext
	```
- [Conda](https://anaconda.org/conda-forge/scattertext) (📥 49K · ⏱️ 18.01.2021):
	```
	conda install -c conda-forge scattertext
	```
</details>
<details><summary><b><a href="https://github.com/Hironsan/anago">anaGo</a></b> (🥉22 ·  ⭐ 1.4K) - Bidirectional LSTM-CRF and ELMo for Named-Entity Recognition, Part-of-.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/Hironsan/anago) (👨‍💻 11 · 🔀 360 · 📦 25 · 📋 110 - 33% open · ⏱️ 01.04.2021):

	```
	git clone https://github.com/Hironsan/anago
	```
- [PyPi](https://pypi.org/project/anago) (📥 3.7K / month):
	```
	pip install anago
	```
</details>
<details><summary><b><a href="https://github.com/deepset-ai/FARM">FARM</a></b> (🥉22 ·  ⭐ 1.2K) - Fast & easy transfer learning for NLP. Harvesting language models.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deepset-ai/FARM) (👨‍💻 32 · 🔀 170 · 📋 350 - 9% open · ⏱️ 07.04.2021):

	```
	git clone https://github.com/deepset-ai/FARM
	```
- [PyPi](https://pypi.org/project/farm) (📥 6.4K / month):
	```
	pip install farm
	```
</details>
<details><summary><b><a href="https://github.com/allenai/scispacy">SciSpacy</a></b> (🥉22 ·  ⭐ 890) - A full spaCy pipeline and models for scientific/biomedical.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/allenai/scispacy) (👨‍💻 20 · 🔀 130 · 📦 240 · 📋 180 - 13% open · ⏱️ 19.04.2021):

	```
	git clone https://github.com/allenai/scispacy
	```
- [PyPi](https://pypi.org/project/scispacy) (📥 17K / month):
	```
	pip install scispacy
	```
</details>
<details><summary><b><a href="https://github.com/Alir3z4/python-stop-words">stop-words</a></b> (🥉22 ·  ⭐ 120 · 💀) - Get list of common stop words in various languages in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/Alir3z4/python-stop-words) (👨‍💻 8 · 🔀 23 · 📦 1.2K · 📋 12 - 25% open · ⏱️ 23.07.2018):

	```
	git clone https://github.com/Alir3z4/python-stop-words
	```
- [PyPi](https://pypi.org/project/stop-words) (📥 79K / month):
	```
	pip install stop-words
	```
</details>
<details><summary><b><a href="https://github.com/snipsco/snips-nlu">Snips NLU</a></b> (🥉21 ·  ⭐ 3.5K · 💀) - Snips Python library to extract meaning from text. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/snipsco/snips-nlu) (👨‍💻 21 · 🔀 470 · 📋 250 - 20% open · ⏱️ 08.02.2020):

	```
	git clone https://github.com/snipsco/snips-nlu
	```
- [PyPi](https://pypi.org/project/snips-nlu) (📥 5.9K / month):
	```
	pip install snips-nlu
	```
</details>
<details><summary><b><a href="https://github.com/NTMC-Community/MatchZoo">MatchZoo</a></b> (🥉21 ·  ⭐ 3.4K · 💀) - Facilitating the design, comparison and sharing of deep.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/NTMC-Community/MatchZoo) (👨‍💻 35 · 🔀 870 · 📦 10 · 📋 460 - 5% open · ⏱️ 24.10.2019):

	```
	git clone https://github.com/NTMC-Community/MatchZoo
	```
- [PyPi](https://pypi.org/project/matchzoo) (📥 200 / month):
	```
	pip install matchzoo
	```
</details>
<details><summary><b><a href="https://github.com/daviddrysdale/python-phonenumbers">phonenumbers</a></b> (🥉21 ·  ⭐ 2.7K) - Python port of Google's libphonenumber. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/daviddrysdale/python-phonenumbers) (👨‍💻 22 · 🔀 320 · 📋 120 - 1% open · ⏱️ 07.04.2021):

	```
	git clone https://github.com/daviddrysdale/python-phonenumbers
	```
- [PyPi](https://pypi.org/project/phonenumbers) (📥 1.6M / month):
	```
	pip install phonenumbers
	```
- [Conda](https://anaconda.org/conda-forge/phonenumbers) (📥 410K · ⏱️ 04.08.2019):
	```
	conda install -c conda-forge phonenumbers
	```
</details>
<details><summary><b><a href="https://github.com/IntelLabs/nlp-architect">NLP Architect</a></b> (🥉21 ·  ⭐ 2.7K) - A model library for exploring state-of-the-art deep learning.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/IntelLabs/nlp-architect) (👨‍💻 36 · 🔀 400 · 📦 7 · 📋 120 - 9% open · ⏱️ 13.04.2021):

	```
	git clone https://github.com/IntelLabs/nlp-architect
	```
- [PyPi](https://pypi.org/project/nlp-architect) (📥 400 / month):
	```
	pip install nlp-architect
	```
</details>
<details><summary><b><a href="https://github.com/asyml/texar">Texar</a></b> (🥉21 ·  ⭐ 2.1K · 💤) - Toolkit for Machine Learning, Natural Language Processing, and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/asyml/texar) (👨‍💻 41 · 🔀 340 · 📦 13 · 📋 160 - 18% open · ⏱️ 29.07.2020):

	```
	git clone https://github.com/asyml/texar
	```
- [PyPi](https://pypi.org/project/texar) (📥 140 / month):
	```
	pip install texar
	```
</details>
<details><summary><b><a href="https://github.com/utterworks/fast-bert">fast-bert</a></b> (🥉21 ·  ⭐ 1.6K) - Super easy library for BERT based NLP models. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/utterworks/fast-bert) (👨‍💻 34 · 🔀 310 · 📋 230 - 60% open · ⏱️ 09.03.2021):

	```
	git clone https://github.com/kaushaltrivedi/fast-bert
	```
- [PyPi](https://pypi.org/project/fast-bert) (📥 3.1K / month):
	```
	pip install fast-bert
	```
</details>
<details><summary><b><a href="https://github.com/awslabs/sockeye">Sockeye</a></b> (🥉21 ·  ⭐ 1K) - Sequence-to-sequence framework with a focus on Neural Machine.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/awslabs/sockeye) (👨‍💻 52 · 🔀 270 · 📋 240 - 6% open · ⏱️ 07.04.2021):

	```
	git clone https://github.com/awslabs/sockeye
	```
- [PyPi](https://pypi.org/project/sockeye) (📥 1.2K / month):
	```
	pip install sockeye
	```
</details>
<details><summary><b><a href="https://github.com/jaraco/inflect">inflect</a></b> (🥉21 ·  ⭐ 510) - Correctly generate plurals, ordinals, indefinite articles; convert numbers.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jaraco/inflect) (👨‍💻 29 · 🔀 56 · 📋 76 - 17% open · ⏱️ 23.03.2021):

	```
	git clone https://github.com/jaraco/inflect
	```
- [PyPi](https://pypi.org/project/inflect) (📥 1.7M / month):
	```
	pip install inflect
	```
- [Conda](https://anaconda.org/conda-forge/inflect) (📥 150K · ⏱️ 03.03.2021):
	```
	conda install -c conda-forge inflect
	```
</details>
<details><summary><b><a href="https://github.com/jbesomi/texthero">Texthero</a></b> (🥉20 ·  ⭐ 2.2K) - Text preprocessing, representation and visualization from zero to hero. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jbesomi/texthero) (👨‍💻 18 · 🔀 190 · 📥 65 · 📋 97 - 47% open · ⏱️ 07.04.2021):

	```
	git clone https://github.com/jbesomi/texthero
	```
- [PyPi](https://pypi.org/project/texthero) (📥 5.4K / month):
	```
	pip install texthero
	```
</details>
<details><summary><b><a href="https://github.com/Delta-ML/delta">DELTA</a></b> (🥉20 ·  ⭐ 1.4K) - DELTA is a deep learning based natural language and speech.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/Delta-ML/delta) (👨‍💻 41 · 🔀 290 · 📋 72 - 4% open · ⏱️ 17.12.2020):

	```
	git clone https://github.com/Delta-ML/delta
	```
- [PyPi](https://pypi.org/project/delta-nlp) (📥 47 / month):
	```
	pip install delta-nlp
	```
- [Docker Hub](https://hub.docker.com/r/zh794390558/delta) (📥 12K · ⏱️ 27.04.2021):
	```
	docker pull zh794390558/delta
	```
</details>
<details><summary><b><a href="https://github.com/VKCOM/YouTokenToMe">YouTokenToMe</a></b> (🥉20 ·  ⭐ 740) - Unsupervised text tokenizer focused on computational efficiency. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/VKCOM/YouTokenToMe) (👨‍💻 6 · 🔀 46 · 📦 110 · 📋 43 - 48% open · ⏱️ 28.01.2021):

	```
	git clone https://github.com/vkcom/youtokentome
	```
- [PyPi](https://pypi.org/project/youtokentome) (📥 17K / month):
	```
	pip install youtokentome
	```
</details>
<details><summary><b><a href="https://github.com/minimaxir/gpt-2-simple">gpt-2-simple</a></b> (🥉19 ·  ⭐ 2.6K) - Python package to easily retrain OpenAI's GPT-2 text-.. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/minimaxir/gpt-2-simple) (👨‍💻 17 · 🔀 540 · 📥 220 · 📋 230 - 58% open · ⏱️ 14.02.2021):

	```
	git clone https://github.com/minimaxir/gpt-2-simple
	```
- [PyPi](https://pypi.org/project/gpt-2-simple) (📥 11K / month):
	```
	pip install gpt-2-simple
	```
</details>
<details><summary><b><a href="https://github.com/BrikerMan/Kashgari">Kashgari</a></b> (🥉19 ·  ⭐ 2.1K) - Kashgari is a production-level NLP Transfer learning framework.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/BrikerMan/Kashgari) (👨‍💻 19 · 🔀 390 · 📦 28 · 📋 350 - 9% open · ⏱️ 21.03.2021):

	```
	git clone https://github.com/BrikerMan/Kashgari
	```
- [PyPi](https://pypi.org/project/kashgari-tf) (📥 250 / month):
	```
	pip install kashgari-tf
	```
</details>
<details><summary><b><a href="https://github.com/IndicoDataSolutions/finetune">finetune</a></b> (🥉19 ·  ⭐ 640) - Scikit-learn style model finetuning for NLP. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/IndicoDataSolutions/finetune) (👨‍💻 19 · 🔀 68 · 📦 9 · 📋 140 - 14% open · ⏱️ 19.03.2021):

	```
	git clone https://github.com/IndicoDataSolutions/finetune
	```
- [PyPi](https://pypi.org/project/finetune) (📥 380 / month):
	```
	pip install finetune
	```
</details>
<details><summary><b><a href="https://github.com/vrasneur/pyfasttext">pyfasttext</a></b> (🥉19 ·  ⭐ 230 · 💀) - Yet another Python binding for fastText. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/vrasneur/pyfasttext) (👨‍💻 4 · 🔀 30 · 📥 320 · 📦 150 · 📋 49 - 42% open · ⏱️ 08.12.2018):

	```
	git clone https://github.com/vrasneur/pyfasttext
	```
- [PyPi](https://pypi.org/project/pyfasttext) (📥 3.9K / month):
	```
	pip install pyfasttext
	```
</details>
<details><summary><b><a href="https://github.com/NVIDIA/NeMo">NeMo</a></b> (🥉18 ·  ⭐ 2.6K) - NeMo: a toolkit for conversational AI. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/NVIDIA/NeMo) (👨‍💻 90 · 🔀 450 · 📥 450 · 📋 500 - 13% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/NVIDIA/NeMo
	```
- [PyPi](https://pypi.org/project/nemo-toolkit) (📥 6.8K / month):
	```
	pip install nemo-toolkit
	```
</details>
<details><summary><b><a href="https://github.com/PKSHATechnology-Research/camphr">Camphr</a></b> (🥉18 ·  ⭐ 330) - spaCy plugin for Transformers , Udify, ELmo, etc. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code>spacy</code></summary>

- [GitHub](https://github.com/PKSHATechnology-Research/camphr) (👨‍💻 7 · 🔀 17 · 📋 23 - 8% open · ⏱️ 02.04.2021):

	```
	git clone https://github.com/PKSHATechnology-Research/camphr
	```
- [PyPi](https://pypi.org/project/camphr) (📥 1.1K / month):
	```
	pip install camphr
	```
</details>
<details><summary><b><a href="https://github.com/textpipe/textpipe">textpipe</a></b> (🥉17 ·  ⭐ 290) - Textpipe: clean and extract metadata from text. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/textpipe/textpipe) (👨‍💻 27 · 🔀 20 · 📦 7 · 📋 40 - 37% open · ⏱️ 25.01.2021):

	```
	git clone https://github.com/textpipe/textpipe
	```
- [PyPi](https://pypi.org/project/textpipe) (📥 2.7K / month):
	```
	pip install textpipe
	```
</details>
<details><summary><b><a href="https://github.com/Franck-Dernoncourt/NeuroNER">NeuroNER</a></b> (🥉16 ·  ⭐ 1.5K · 💀) - Named-entity recognition using neural networks. Easy-to-use and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Franck-Dernoncourt/NeuroNER) (👨‍💻 7 · 🔀 440 · 📦 9 · 📋 150 - 54% open · ⏱️ 02.10.2019):

	```
	git clone https://github.com/Franck-Dernoncourt/NeuroNER
	```
- [PyPi](https://pypi.org/project/pyneuroner) (📥 250 / month):
	```
	pip install pyneuroner
	```
</details>
<details><summary><b><a href="https://github.com/anhaidgroup/deepmatcher">DeepMatcher</a></b> (🥉16 ·  ⭐ 300 · 💤) - Python package for performing Entity and Text Matching using.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/anhaidgroup/deepmatcher) (👨‍💻 7 · 🔀 71 · 📦 12 · 📋 64 - 70% open · ⏱️ 20.04.2020):

	```
	git clone https://github.com/anhaidgroup/deepmatcher
	```
- [PyPi](https://pypi.org/project/deepmatcher) (📥 610 / month):
	```
	pip install deepmatcher
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/translate">Translate</a></b> (🥉15 ·  ⭐ 690) - Translate - a PyTorch Language Library. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/translate) (👨‍💻 86 · 🔀 170 · 📋 38 - 28% open · ⏱️ 23.04.2021):

	```
	git clone https://github.com/pytorch/translate
	```
- [PyPi](https://pypi.org/project/pytorch-translate) (📥 18 / month):
	```
	pip install pytorch-translate
	```
</details>
<details><summary><b><a href="https://github.com/feedly/transfer-nlp">TransferNLP</a></b> (🥉15 ·  ⭐ 290 · 💤) - NLP library designed for reproducible experimentation.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/feedly/transfer-nlp) (👨‍💻 7 · 🔀 17 · 📋 23 - 13% open · ⏱️ 28.05.2020):

	```
	git clone https://github.com/feedly/transfer-nlp
	```
- [PyPi](https://pypi.org/project/transfer-nlp) (📥 180 / month):
	```
	pip install transfer-nlp
	```
</details>
<details><summary><b><a href="https://github.com/victordibia/neuralqa">NeuralQA</a></b> (🥉15 ·  ⭐ 190) - NeuralQA: A Usable Library for Question Answering on Large Datasets with.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/victordibia/neuralqa) (👨‍💻 3 · 🔀 24 · 📦 2 · 📋 27 - 70% open · ⏱️ 16.12.2020):

	```
	git clone https://github.com/victordibia/neuralqa
	```
- [PyPi](https://pypi.org/project/neuralqa) (📥 210 / month):
	```
	pip install neuralqa
	```
</details>
<details><summary><b><a href="https://github.com/thunlp/OpenNRE">OpenNRE</a></b> (🥉14 ·  ⭐ 3.1K) - An Open-Source Package for Neural Relation Extraction (NRE). <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/thunlp/OpenNRE) (👨‍💻 9 · 🔀 840 · 📋 310 - 7% open · ⏱️ 09.03.2021):

	```
	git clone https://github.com/thunlp/OpenNRE
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/vizseq">VizSeq</a></b> (🥉14 ·  ⭐ 330) - An Analysis Toolkit for Natural Language Generation (Translation,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebookresearch/vizseq) (👨‍💻 3 · 🔀 41 · 📦 2 · 📋 13 - 38% open · ⏱️ 20.04.2021):

	```
	git clone https://github.com/facebookresearch/vizseq
	```
- [PyPi](https://pypi.org/project/vizseq) (📥 220 / month):
	```
	pip install vizseq
	```
</details>
<details><summary><b><a href="https://github.com/abelriboulot/onnxt5">ONNX-T5</a></b> (🥉14 ·  ⭐ 150) - Summarization, translation, sentiment-analysis, text-generation and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/abelriboulot/onnxt5) (👨‍💻 3 · 🔀 19 · 📋 11 - 45% open · ⏱️ 28.01.2021):

	```
	git clone https://github.com/abelriboulot/onnxt5
	```
- [PyPi](https://pypi.org/project/onnxt5) (📥 180 / month):
	```
	pip install onnxt5
	```
</details>
<details><summary><b><a href="https://github.com/as-ideas/headliner">Headliner</a></b> (🥉13 ·  ⭐ 220 · 💀) - Easy training and deployment of seq2seq models. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/as-ideas/headliner) (👨‍💻 2 · 🔀 37 · 📦 3 · 📋 14 - 7% open · ⏱️ 14.02.2020):

	```
	git clone https://github.com/as-ideas/headliner
	```
- [PyPi](https://pypi.org/project/headliner) (📥 410 / month):
	```
	pip install headliner
	```
</details>
<details><summary><b><a href="https://github.com/shaypal5/skift">skift</a></b> (🥉13 ·  ⭐ 220) - scikit-learn wrappers for Python fastText. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/shaypal5/skift) (👨‍💻 7 · 🔀 20 · 📦 8 · 📋 10 - 20% open · ⏱️ 31.03.2021):

	```
	git clone https://github.com/shaypal5/skift
	```
- [PyPi](https://pypi.org/project/skift) (📥 1.6K / month):
	```
	pip install skift
	```
</details>
<details><summary><b><a href="https://github.com/textvec/textvec">textvec</a></b> (🥉12 ·  ⭐ 170) - Text vectorization tool to outperform TFIDF for classification tasks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/textvec/textvec) (👨‍💻 5 · 🔀 20 · 📦 2 · 📋 8 - 25% open · ⏱️ 03.12.2020):

	```
	git clone https://github.com/textvec/textvec
	```
- [PyPi](https://pypi.org/project/textvec) (📥 160 / month):
	```
	pip install textvec
	```
</details>
<br>

## Image Data

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for image & video processing, manipulation, and augmentation as well as libraries for computer vision tasks such as facial recognition, object detection, and classification._

<details><summary><b><a href="https://github.com/python-pillow/Pillow">Pillow</a></b> (🥇40 ·  ⭐ 8.5K) - The friendly PIL fork (Python Imaging Library). <code><a href="https://tldrlegal.com/search?q=PIL">❗️PIL</a></code></summary>

- [GitHub](https://github.com/python-pillow/Pillow) (👨‍💻 360 · 🔀 1.5K · 📦 450K · 📋 2.2K - 8% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/python-pillow/Pillow
	```
- [PyPi](https://pypi.org/project/Pillow) (📥 32M / month):
	```
	pip install Pillow
	```
- [Conda](https://anaconda.org/conda-forge/pillow) (📥 8.2M · ⏱️ 08.04.2021):
	```
	conda install -c conda-forge pillow
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/vision">torchvision</a></b> (🥇36 ·  ⭐ 8.9K) - Datasets, Transforms and Models specific to Computer Vision. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/vision) (👨‍💻 380 · 🔀 4.5K · 📦 48K · 📋 1.6K - 21% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/pytorch/vision
	```
- [PyPi](https://pypi.org/project/torchvision) (📥 1.5M / month):
	```
	pip install torchvision
	```
- [Conda](https://anaconda.org/conda-forge/torchvision) (📥 54K · ⏱️ 22.04.2021):
	```
	conda install -c conda-forge torchvision
	```
</details>
<details><summary><b><a href="https://github.com/aleju/imgaug">imgaug</a></b> (🥇32 ·  ⭐ 11K · 💤) - Image augmentation for machine learning experiments. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/aleju/imgaug) (👨‍💻 36 · 🔀 2K · 📦 6.1K · 📋 440 - 52% open · ⏱️ 01.06.2020):

	```
	git clone https://github.com/aleju/imgaug
	```
- [PyPi](https://pypi.org/project/imgaug) (📥 260K / month):
	```
	pip install imgaug
	```
- [Conda](https://anaconda.org/conda-forge/imgaug) (📥 39K · ⏱️ 14.02.2020):
	```
	conda install -c conda-forge imgaug
	```
</details>
<details><summary><b><a href="https://github.com/imageio/imageio">imageio</a></b> (🥇32 ·  ⭐ 870) - Python library for reading and writing image data. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/imageio/imageio) (👨‍💻 77 · 🔀 180 · 📦 40K · 📋 350 - 19% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/imageio/imageio
	```
- [PyPi](https://pypi.org/project/imageio) (📥 5.4M / month):
	```
	pip install imageio
	```
- [Conda](https://anaconda.org/conda-forge/imageio) (📥 1.9M · ⏱️ 06.07.2020):
	```
	conda install -c conda-forge imageio
	```
</details>
<details><summary><b><a href="https://github.com/scikit-image/scikit-image">scikit-image</a></b> (🥇31 ·  ⭐ 4.3K) - Image processing in Python. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/scikit-image/scikit-image) (👨‍💻 490 · 🔀 1.7K · 📦 67K · 📋 2K - 24% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/scikit-image/scikit-image
	```
- [PyPi](https://pypi.org/project/scikit-image) (📥 5.1M / month):
	```
	pip install scikit-image
	```
- [Conda](https://anaconda.org/conda-forge/scikit-image) (📥 2.4M · ⏱️ 21.01.2021):
	```
	conda install -c conda-forge scikit-image
	```
</details>
<details><summary><b><a href="https://github.com/Zulko/moviepy">MoviePy</a></b> (🥈30 ·  ⭐ 7.5K) - Video editing with Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Zulko/moviepy) (👨‍💻 140 · 🔀 1K · 📦 7.1K · 📋 1K - 27% open · ⏱️ 15.04.2021):

	```
	git clone https://github.com/Zulko/moviepy
	```
- [PyPi](https://pypi.org/project/moviepy) (📥 600K / month):
	```
	pip install moviepy
	```
- [Conda](https://anaconda.org/conda-forge/moviepy) (📥 79K · ⏱️ 23.02.2020):
	```
	conda install -c conda-forge moviepy
	```
</details>
<details><summary><b><a href="https://github.com/emcconville/wand">Wand</a></b> (🥈30 ·  ⭐ 1.1K) - The ctypes-based simple ImageMagick binding for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/emcconville/wand) (👨‍💻 95 · 🔀 180 · 📥 5.2K · 📦 4.1K · 📋 340 - 3% open · ⏱️ 29.03.2021):

	```
	git clone https://github.com/emcconville/wand
	```
- [PyPi](https://pypi.org/project/wand) (📥 280K / month):
	```
	pip install wand
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/detectron2">detectron2</a></b> (🥈29 ·  ⭐ 16K) - Detectron2 is FAIR's next-generation platform for object.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/detectron2) (👨‍💻 160 · 🔀 4K · 📦 220 · 📋 2.4K - 3% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/facebookresearch/detectron2
	```
- [Conda](https://anaconda.org/conda-forge/detectron2) (📥 17K · ⏱️ 05.08.2020):
	```
	conda install -c conda-forge detectron2
	```
</details>
<details><summary><b><a href="https://github.com/albumentations-team/albumentations">Albumentations</a></b> (🥈29 ·  ⭐ 7.8K) - Fast image augmentation library and an easy-to-use wrapper.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/albumentations-team/albumentations) (👨‍💻 76 · 🔀 990 · 📦 3.4K · 📋 420 - 39% open · ⏱️ 02.04.2021):

	```
	git clone https://github.com/albumentations-team/albumentations
	```
- [PyPi](https://pypi.org/project/albumentations) (📥 140K / month):
	```
	pip install albumentations
	```
- [Conda](https://anaconda.org/conda-forge/albumentations) (📥 18K · ⏱️ 29.11.2020):
	```
	conda install -c conda-forge albumentations
	```
</details>
<details><summary><b><a href="https://github.com/JohannesBuchner/imagehash">ImageHash</a></b> (🥈29 ·  ⭐ 1.9K) - A Python Perceptual Image Hashing Module. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/JohannesBuchner/imagehash) (👨‍💻 17 · 🔀 260 · 📦 2.4K · 📋 89 - 15% open · ⏱️ 03.01.2021):

	```
	git clone https://github.com/JohannesBuchner/imagehash
	```
- [PyPi](https://pypi.org/project/ImageHash) (📥 770K / month):
	```
	pip install ImageHash
	```
- [Conda](https://anaconda.org/conda-forge/imagehash) (📥 110K · ⏱️ 19.11.2020):
	```
	conda install -c conda-forge imagehash
	```
</details>
<details><summary><b><a href="https://github.com/rwightman/pytorch-image-models">PyTorch Image Models</a></b> (🥈28 ·  ⭐ 9.2K) - PyTorch image models, scripts, pretrained weights --.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rwightman/pytorch-image-models) (👨‍💻 40 · 🔀 1.4K · 📥 340K · 📦 490 · 📋 290 - 6% open · ⏱️ 19.04.2021):

	```
	git clone https://github.com/rwightman/pytorch-image-models
	```
</details>
<details><summary><b><a href="https://github.com/dmlc/gluon-cv">GluonCV</a></b> (🥈28 ·  ⭐ 4.7K) - Gluon CV Toolkit. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/dmlc/gluon-cv) (👨‍💻 110 · 🔀 1.1K · 📦 480 · 📋 750 - 49% open · ⏱️ 12.04.2021):

	```
	git clone https://github.com/dmlc/gluon-cv
	```
- [PyPi](https://pypi.org/project/gluoncv) (📥 83K / month):
	```
	pip install gluoncv
	```
</details>
<details><summary><b><a href="https://github.com/glfw/glfw">glfw</a></b> (🥈26 ·  ⭐ 7.6K) - A multi-platform library for OpenGL, OpenGL ES, Vulkan, window and input. <code><a href="https://tldrlegal.com/search?q=Zlib">❗️Zlib</a></code></summary>

- [GitHub](https://github.com/glfw/glfw) (👨‍💻 170 · 🔀 2.5K · 📥 2.3M · 📋 1.4K - 27% open · ⏱️ 22.04.2021):

	```
	git clone https://github.com/glfw/glfw
	```
- [PyPi](https://pypi.org/project/glfw) (📥 43K / month):
	```
	pip install glfw
	```
- [Conda](https://anaconda.org/conda-forge/glfw) (📥 29K · ⏱️ 08.04.2021):
	```
	conda install -c conda-forge glfw
	```
</details>
<details><summary><b><a href="https://github.com/OlafenwaMoses/ImageAI">imageai</a></b> (🥈26 ·  ⭐ 6.1K) - A python library built to empower developers to build applications and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/OlafenwaMoses/ImageAI) (👨‍💻 13 · 🔀 1.7K · 📥 570K · 📦 800 · 📋 600 - 31% open · ⏱️ 05.01.2021):

	```
	git clone https://github.com/OlafenwaMoses/ImageAI
	```
- [PyPi](https://pypi.org/project/imageai) (📥 16K / month):
	```
	pip install imageai
	```
</details>
<details><summary><b><a href="https://github.com/kornia/kornia">Kornia</a></b> (🥈26 ·  ⭐ 3.9K) - Open Source Differentiable Computer Vision Library for.. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/kornia/kornia) (👨‍💻 95 · 🔀 380 · 📦 350 · 📋 370 - 18% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/kornia/kornia
	```
- [PyPi](https://pypi.org/project/kornia) (📥 45K / month):
	```
	pip install kornia
	```
</details>
<details><summary><b><a href="https://github.com/jrosebr1/imutils">imutils</a></b> (🥈26 ·  ⭐ 3.6K) - A series of convenience functions to make basic image processing.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jrosebr1/imutils) (👨‍💻 20 · 🔀 890 · 📦 14K · 📋 150 - 49% open · ⏱️ 15.01.2021):

	```
	git clone https://github.com/jrosebr1/imutils
	```
- [PyPi](https://pypi.org/project/imutils) (📥 240K / month):
	```
	pip install imutils
	```
- [Conda](https://anaconda.org/conda-forge/imutils) (📥 48K · ⏱️ 15.01.2021):
	```
	conda install -c conda-forge imutils
	```
</details>
<details><summary><b><a href="https://github.com/ageitgey/face_recognition">Face Recognition</a></b> (🥈25 ·  ⭐ 40K · 💤) - The world's simplest facial recognition api for.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/ageitgey/face_recognition) (👨‍💻 45 · 🔀 11K · 📥 440 · 📋 1.1K - 52% open · ⏱️ 26.09.2020):

	```
	git clone https://github.com/ageitgey/face_recognition
	```
- [PyPi](https://pypi.org/project/face_recognition) (📥 52K / month):
	```
	pip install face_recognition
	```
</details>
<details><summary><b><a href="https://github.com/open-mmlab/mmdetection">MMDetection</a></b> (🥈25 ·  ⭐ 15K) - OpenMMLab Detection Toolbox and Benchmark. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/open-mmlab/mmdetection) (👨‍💻 210 · 🔀 4.7K · 📦 40 · 📋 3.7K - 6% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/open-mmlab/mmdetection
	```
</details>
<details><summary><b><a href="https://github.com/timesler/facenet-pytorch">facenet-pytorch</a></b> (🥈25 ·  ⭐ 2K) - Pretrained Pytorch face detection (MTCNN) and recognition.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/timesler/facenet-pytorch) (👨‍💻 14 · 🔀 430 · 📥 85K · 📦 340 · 📋 120 - 28% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/timesler/facenet-pytorch
	```
- [PyPi](https://pypi.org/project/facenet-pytorch) (📥 26K / month):
	```
	pip install facenet-pytorch
	```
</details>
<details><summary><b><a href="https://github.com/chainer/chainercv">chainercv</a></b> (🥈25 ·  ⭐ 1.4K · 💀) - ChainerCV: a Library for Deep Learning in Computer Vision. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/chainer/chainercv) (👨‍💻 39 · 🔀 310 · 📦 240 · 📋 200 - 16% open · ⏱️ 07.01.2020):

	```
	git clone https://github.com/chainer/chainercv
	```
- [PyPi](https://pypi.org/project/chainercv) (📥 5.4K / month):
	```
	pip install chainercv
	```
</details>
<details><summary><b><a href="https://github.com/deepinsight/insightface">InsightFace</a></b> (🥉24 ·  ⭐ 9K) - Face Analysis Project on MXNet and PyTorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deepinsight/insightface) (👨‍💻 17 · 🔀 3K · 📦 66 · 📋 1.4K - 50% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/deepinsight/insightface
	```
- [PyPi](https://pypi.org/project/insightface) (📥 3.3K / month):
	```
	pip install insightface
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/pytorch3d">PyTorch3D</a></b> (🥉24 ·  ⭐ 4.7K) - PyTorch3D is FAIR's library of reusable components for.. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/pytorch3d) (👨‍💻 57 · 🔀 570 · 📦 70 · 📋 560 - 13% open · ⏱️ 22.04.2021):

	```
	git clone https://github.com/facebookresearch/pytorch3d
	```
- [PyPi](https://pypi.org/project/pytorch3d) (📥 8.4K / month):
	```
	pip install pytorch3d
	```
- [Conda](https://anaconda.org/pytorch3d/pytorch3d) (📥 9.2K · ⏱️ 09.02.2021):
	```
	conda install -c pytorch3d pytorch3d
	```
</details>
<details><summary><b><a href="https://github.com/mdbloice/Augmentor">Augmentor</a></b> (🥉23 ·  ⭐ 4.4K · 💀) - Image augmentation library in Python for machine learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mdbloice/Augmentor) (👨‍💻 22 · 🔀 790 · 📦 300 · 📋 170 - 61% open · ⏱️ 09.03.2020):

	```
	git clone https://github.com/mdbloice/Augmentor
	```
- [PyPi](https://pypi.org/project/Augmentor) (📥 15K / month):
	```
	pip install Augmentor
	```
</details>
<details><summary><b><a href="https://github.com/idealo/imagededup">Image Deduplicator</a></b> (🥉23 ·  ⭐ 3.5K) - Finding duplicate images made easy!. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/idealo/imagededup) (👨‍💻 9 · 🔀 290 · 📦 11 · 📋 75 - 24% open · ⏱️ 23.11.2020):

	```
	git clone https://github.com/idealo/imagededup
	```
- [PyPi](https://pypi.org/project/imagededup) (📥 2.3K / month):
	```
	pip install imagededup
	```
</details>
<details><summary><b><a href="https://github.com/opencv/opencv-python">opencv-python</a></b> (🥉23 ·  ⭐ 1.9K) - Automated CI toolchain to produce precompiled opencv-.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/opencv/opencv-python) (👨‍💻 27 · 🔀 350 · 📋 420 - 6% open · ⏱️ 28.12.2020):

	```
	git clone https://github.com/skvark/opencv-python
	```
- [PyPi](https://pypi.org/project/opencv-python) (📥 4.9M / month):
	```
	pip install opencv-python
	```
</details>
<details><summary><b><a href="https://github.com/ipazc/mtcnn">mtcnn</a></b> (🥉23 ·  ⭐ 1.5K) - MTCNN face detection implementation for TensorFlow, as a PIP package. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/ipazc/mtcnn) (👨‍💻 14 · 🔀 380 · 📦 1K · 📋 90 - 60% open · ⏱️ 13.01.2021):

	```
	git clone https://github.com/ipazc/mtcnn
	```
- [PyPi](https://pypi.org/project/mtcnn) (📥 21K / month):
	```
	pip install mtcnn
	```
</details>
<details><summary><b><a href="https://github.com/1adrianb/face-alignment">Face Alignment</a></b> (🥉22 ·  ⭐ 4.9K) - 2D and 3D Face alignment library build using pytorch. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/1adrianb/face-alignment) (👨‍💻 22 · 🔀 1K · 📋 240 - 15% open · ⏱️ 03.03.2021):

	```
	git clone https://github.com/1adrianb/face-alignment
	```
- [PyPi](https://pypi.org/project/face-alignment) (📥 7K / month):
	```
	pip install face-alignment
	```
</details>
<details><summary><b><a href="https://github.com/abhiTronix/vidgear">vidgear</a></b> (🥉22 ·  ⭐ 1.7K) - High-performance cross-platform Video Processing Python framework.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/abhiTronix/vidgear) (👨‍💻 6 · 🔀 120 · 📥 340 · 📦 99 · 📋 140 - 2% open · ⏱️ 25.04.2021):

	```
	git clone https://github.com/abhiTronix/vidgear
	```
- [PyPi](https://pypi.org/project/vidgear) (📥 2.2K / month):
	```
	pip install vidgear
	```
</details>
<details><summary><b><a href="https://github.com/nicolas-chaulet/torch-points3d">Torch Points 3D</a></b> (🥉22 ·  ⭐ 1.2K) - Pytorch framework for doing deep learning on point clouds. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/nicolas-chaulet/torch-points3d) (👨‍💻 21 · 🔀 180 · 📦 2 · 📋 230 - 21% open · ⏱️ 21.04.2021):

	```
	git clone https://github.com/nicolas-chaulet/torch-points3d
	```
- [PyPi](https://pypi.org/project/torch-points3d) (📥 560 / month):
	```
	pip install torch-points3d
	```
</details>
<details><summary><b><a href="https://github.com/luispedro/mahotas">mahotas</a></b> (🥉22 ·  ⭐ 680) - Computer Vision in Python. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/luispedro/mahotas) (👨‍💻 30 · 🔀 130 · 📦 620 · 📋 70 - 18% open · ⏱️ 13.01.2021):

	```
	git clone https://github.com/luispedro/mahotas
	```
- [PyPi](https://pypi.org/project/mahotas) (📥 32K / month):
	```
	pip install mahotas
	```
- [Conda](https://anaconda.org/conda-forge/mahotas) (📥 270K · ⏱️ 22.01.2021):
	```
	conda install -c conda-forge mahotas
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/mmf">MMF</a></b> (🥉21 ·  ⭐ 4.3K) - A modular framework for vision & language multimodal research from.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/mmf) (👨‍💻 62 · 🔀 640 · 📦 7 · 📋 480 - 22% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/facebookresearch/mmf
	```
- [PyPi](https://pypi.org/project/mmf) (📥 810 / month):
	```
	pip install mmf
	```
</details>
<details><summary><b><a href="https://github.com/lucidrains/vit-pytorch">vit-pytorch</a></b> (🥉21 ·  ⭐ 3.9K · 🐣) - Implementation of Vision Transformer, a simple way to.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/lucidrains/vit-pytorch) (👨‍💻 6 · 🔀 430 · 📦 13 · 📋 90 - 41% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/lucidrains/vit-pytorch
	```
- [PyPi](https://pypi.org/project/vit-pytorch) (📥 3.7K / month):
	```
	pip install vit-pytorch
	```
</details>
<details><summary><b><a href="https://github.com/qubvel/segmentation_models">segmentation_models</a></b> (🥉21 ·  ⭐ 3.1K · 💤) - Segmentation models with pretrained backbones. Keras.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/qubvel/segmentation_models) (👨‍💻 14 · 🔀 730 · 📋 400 - 39% open · ⏱️ 17.04.2020):

	```
	git clone https://github.com/qubvel/segmentation_models
	```
- [PyPi](https://pypi.org/project/segmentation_models) (📥 18K / month):
	```
	pip install segmentation_models
	```
</details>
<details><summary><b><a href="https://github.com/idealo/image-super-resolution">Image Super-Resolution</a></b> (🥉21 ·  ⭐ 2.7K) - Super-scale your images and run experiments with.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/idealo/image-super-resolution) (👨‍💻 9 · 🔀 510 · 📦 47 · 📋 170 - 39% open · ⏱️ 11.11.2020):

	```
	git clone https://github.com/idealo/image-super-resolution
	```
- [PyPi](https://pypi.org/project/ISR) (📥 4.9K / month):
	```
	pip install ISR
	```
- [Docker Hub](https://hub.docker.com/r/idealo/image-super-resolution-gpu) (📥 140 · ⏱️ 01.04.2019):
	```
	docker pull idealo/image-super-resolution-gpu
	```
</details>
<details><summary><b><a href="https://github.com/uploadcare/pillow-simd">Pillow-SIMD</a></b> (🥉21 ·  ⭐ 1.6K · 💤) - The friendly PIL fork. <code><a href="https://tldrlegal.com/search?q=PIL">❗️PIL</a></code></summary>

- [GitHub](https://github.com/uploadcare/pillow-simd) (👨‍💻 310 · 🔀 67 · 📦 390 · 📋 65 - 16% open · ⏱️ 02.06.2020):

	```
	git clone https://github.com/uploadcare/pillow-simd
	```
- [PyPi](https://pypi.org/project/pillow-simd) (📥 34K / month):
	```
	pip install pillow-simd
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/ClassyVision">Classy Vision</a></b> (🥉21 ·  ⭐ 1.2K) - An end-to-end PyTorch framework for image and video.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/ClassyVision) (👨‍💻 61 · 🔀 210 · 📋 65 - 20% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/facebookresearch/ClassyVision
	```
- [PyPi](https://pypi.org/project/classy_vision) (📥 420 / month):
	```
	pip install classy_vision
	```
- [Conda](https://anaconda.org/conda-forge/classy_vision) (📥 7.1K · ⏱️ 11.12.2020):
	```
	conda install -c conda-forge classy_vision
	```
</details>
<details><summary><b><a href="https://github.com/lightly-ai/lightly">lightly</a></b> (🥉21 ·  ⭐ 770 · 🐣) - A python library for self-supervised learning on images. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/lightly-ai/lightly) (👨‍💻 9 · 🔀 45 · 📦 11 · 📋 150 - 25% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/lightly-ai/lightly
	```
- [PyPi](https://pypi.org/project/lightly) (📥 3.4K / month):
	```
	pip install lightly
	```
</details>
<details><summary><b><a href="https://github.com/CellProfiler/CellProfiler">CellProfiler</a></b> (🥉21 ·  ⭐ 560) - An open-source application for biological image analysis. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/CellProfiler/CellProfiler) (👨‍💻 120 · 🔀 270 · 📥 900 · 📦 4 · 📋 3K - 5% open · ⏱️ 16.04.2021):

	```
	git clone https://github.com/CellProfiler/CellProfiler
	```
- [PyPi](https://pypi.org/project/cellprofiler) (📥 650 / month):
	```
	pip install cellprofiler
	```
</details>
<details><summary><b><a href="https://github.com/jasmcaus/caer">Caer</a></b> (🥉21 ·  ⭐ 480) - A lightweight Computer Vision library. Scale your models, not boilerplate. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jasmcaus/caer) (👨‍💻 6 · 🔀 36 · 📥 14 · 📋 13 - 30% open · ⏱️ 24.04.2021):

	```
	git clone https://github.com/jasmcaus/caer
	```
- [PyPi](https://pypi.org/project/caer) (📥 23K / month):
	```
	pip install caer
	```
</details>
<details><summary><b><a href="https://github.com/PaddlePaddle/PaddleDetection">PaddleDetection</a></b> (🥉20 ·  ⭐ 2.6K) - Object detection and instance segmentation toolkit.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PaddlePaddle/PaddleDetection) (👨‍💻 54 · 🔀 720 · 📦 5 · 📋 1.4K - 18% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/PaddlePaddle/PaddleDetection
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/graphics">tensorflow-graphics</a></b> (🥉20 ·  ⭐ 2.4K) - TensorFlow Graphics: Differentiable Graphics Layers.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/graphics) (👨‍💻 32 · 🔀 280 · 📦 1 · 📋 140 - 41% open · ⏱️ 19.04.2021):

	```
	git clone https://github.com/tensorflow/graphics
	```
- [PyPi](https://pypi.org/project/tensorflow-graphics) (📥 2.8K / month):
	```
	pip install tensorflow-graphics
	```
</details>
<details><summary><b><a href="https://github.com/tryolabs/luminoth">Luminoth</a></b> (🥉20 ·  ⭐ 2.4K · 💀) - Deep Learning toolkit for Computer Vision. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tryolabs/luminoth) (👨‍💻 15 · 🔀 410 · 📥 11K · 📦 29 · 📋 180 - 28% open · ⏱️ 07.01.2020):

	```
	git clone https://github.com/tryolabs/luminoth
	```
- [PyPi](https://pypi.org/project/luminoth) (📥 960 / month):
	```
	pip install luminoth
	```
</details>
<details><summary><b><a href="https://github.com/libvips/pyvips">pyvips</a></b> (🥉20 ·  ⭐ 310) - python binding for libvips using cffi. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/libvips/pyvips) (👨‍💻 10 · 🔀 26 · 📦 180 · 📋 220 - 33% open · ⏱️ 24.02.2021):

	```
	git clone https://github.com/libvips/pyvips
	```
- [PyPi](https://pypi.org/project/pyvips) (📥 11K / month):
	```
	pip install pyvips
	```
- [Conda](https://anaconda.org/conda-forge/pyvips) (📥 8.4K · ⏱️ 14.10.2020):
	```
	conda install -c conda-forge pyvips
	```
</details>
<details><summary><b><a href="https://github.com/tryolabs/norfair">Norfair</a></b> (🥉18 ·  ⭐ 980) - Lightweight Python library for adding real-time 2D object tracking to.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/tryolabs/norfair) (👨‍💻 8 · 🔀 65 · 📋 21 - 19% open · ⏱️ 16.03.2021):

	```
	git clone https://github.com/tryolabs/norfair
	```
- [PyPi](https://pypi.org/project/norfair) (📥 820 / month):
	```
	pip install norfair
	```
</details>
<details><summary><b><a href="https://github.com/EdjoLabs/image-match">image-match</a></b> (🥉17 ·  ⭐ 2.6K) - Quickly search over billions of images. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/EdjoLabs/image-match) (👨‍💻 17 · 🔀 360 · 📋 92 - 47% open · ⏱️ 04.01.2021):

	```
	git clone https://github.com/EdjoLabs/image-match
	```
- [PyPi](https://pypi.org/project/image_match) (📥 1.2K / month):
	```
	pip install image_match
	```
</details>
<details><summary><b><a href="https://github.com/hhatto/nude.py">nude.py</a></b> (🥉17 ·  ⭐ 800) - Nudity detection with Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/hhatto/nude.py) (👨‍💻 12 · 🔀 130 · 📦 190 · 📋 8 - 75% open · ⏱️ 23.11.2020):

	```
	git clone https://github.com/hhatto/nude.py
	```
- [PyPi](https://pypi.org/project/nudepy) (📥 1.7K / month):
	```
	pip install nudepy
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/pycls">pycls</a></b> (🥉15 ·  ⭐ 1.5K) - Codebase for Image Classification Research, written in PyTorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/pycls) (👨‍💻 10 · 🔀 170 · 📦 3 · 📋 59 - 25% open · ⏱️ 27.03.2021):

	```
	git clone https://github.com/facebookresearch/pycls
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/detr">DE⫶TR</a></b> (🥉14 ·  ⭐ 6.8K) - End-to-End Object Detection with Transformers. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/detr) (👨‍💻 19 · 🔀 1.1K · 📋 310 - 24% open · ⏱️ 15.11.2020):

	```
	git clone https://github.com/facebookresearch/detr
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/SlowFast">PySlowFast</a></b> (🥉14 ·  ⭐ 3.6K) - PySlowFast: video understanding codebase from FAIR for.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/SlowFast) (👨‍💻 20 · 🔀 680 · 📦 2 · 📋 380 - 49% open · ⏱️ 23.04.2021):

	```
	git clone https://github.com/facebookresearch/SlowFast
	```
</details>
<br>

## Graph Data

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for graph processing, clustering, embedding, and machine learning tasks._

<details><summary><b><a href="https://github.com/networkx/networkx">networkx</a></b> (🥇31 ·  ⭐ 9K) - Network Analysis in Python. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/networkx/networkx) (👨‍💻 510 · 🔀 2.2K · 📥 51 · 📦 73K · 📋 2.5K - 6% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/networkx/networkx
	```
- [PyPi](https://pypi.org/project/networkx) (📥 13M / month):
	```
	pip install networkx
	```
- [Conda](https://anaconda.org/conda-forge/networkx) (📥 3.5M · ⏱️ 04.04.2021):
	```
	conda install -c conda-forge networkx
	```
</details>
<details><summary><b><a href="https://github.com/igraph/python-igraph">igraph</a></b> (🥇28 ·  ⭐ 810) - Python interface for igraph. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/igraph/python-igraph) (👨‍💻 50 · 🔀 180 · 📥 120K · 📦 1.6K · 📋 300 - 5% open · ⏱️ 20.04.2021):

	```
	git clone https://github.com/igraph/python-igraph
	```
- [PyPi](https://pypi.org/project/python-igraph) (📥 88K / month):
	```
	pip install python-igraph
	```
- [Conda](https://anaconda.org/conda-forge/igraph) (📥 210K · ⏱️ 15.04.2021):
	```
	conda install -c conda-forge igraph
	```
</details>
<details><summary><b><a href="https://github.com/rusty1s/pytorch_geometric">PyTorch Geometric</a></b> (🥇27 ·  ⭐ 11K) - Geometric Deep Learning Extension Library for PyTorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rusty1s/pytorch_geometric) (👨‍💻 160 · 🔀 1.8K · 📋 2K - 38% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/rusty1s/pytorch_geometric
	```
- [PyPi](https://pypi.org/project/torch-geometric) (📥 37K / month):
	```
	pip install torch-geometric
	```
</details>
<details><summary><b><a href="https://github.com/dmlc/dgl">dgl</a></b> (🥈25 ·  ⭐ 7.2K) - Python package built to ease deep learning on graph, on top of existing.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/dmlc/dgl) (👨‍💻 120 · 🔀 1.4K · 📋 980 - 19% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/dmlc/dgl
	```
- [PyPi](https://pypi.org/project/dgl) (📥 38K / month):
	```
	pip install dgl
	```
</details>
<details><summary><b><a href="https://github.com/stellargraph/stellargraph">StellarGraph</a></b> (🥈25 ·  ⭐ 1.9K) - StellarGraph - Machine Learning on Graphs. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/stellargraph/stellargraph) (👨‍💻 32 · 🔀 270 · 📦 60 · 📋 920 - 22% open · ⏱️ 18.02.2021):

	```
	git clone https://github.com/stellargraph/stellargraph
	```
- [PyPi](https://pypi.org/project/stellargraph) (📥 6.1K / month):
	```
	pip install stellargraph
	```
</details>
<details><summary><b><a href="https://github.com/snap-stanford/ogb">ogb</a></b> (🥈23 ·  ⭐ 900) - Benchmark datasets, data loaders, and evaluators for graph machine learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/snap-stanford/ogb) (👨‍💻 14 · 🔀 160 · 📦 83 · 📋 130 - 2% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/snap-stanford/ogb
	```
- [PyPi](https://pypi.org/project/ogb) (📥 6.6K / month):
	```
	pip install ogb
	```
</details>
<details><summary><b><a href="https://github.com/eliorc/node2vec">Node2Vec</a></b> (🥈23 ·  ⭐ 680) - Implementation of the node2vec algorithm. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/eliorc/node2vec) (👨‍💻 8 · 🔀 170 · 📦 130 · ⏱️ 16.04.2021):

	```
	git clone https://github.com/eliorc/node2vec
	```
- [PyPi](https://pypi.org/project/node2vec) (📥 11K / month):
	```
	pip install node2vec
	```
- [Conda](https://anaconda.org/conda-forge/node2vec) (📥 17K · ⏱️ 25.04.2020):
	```
	conda install -c conda-forge node2vec
	```
</details>
<details><summary><b><a href="https://github.com/Kozea/pygal">pygal</a></b> (🥈22 ·  ⭐ 2.3K) - PYthon svg GrAph plotting Library. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code></summary>

- [GitHub](https://github.com/Kozea/pygal) (👨‍💻 70 · 🔀 380 · 📋 390 - 38% open · ⏱️ 18.03.2021):

	```
	git clone https://github.com/Kozea/pygal
	```
- [PyPi](https://pypi.org/project/pygal) (📥 110K / month):
	```
	pip install pygal
	```
- [Conda](https://anaconda.org/conda-forge/pygal) (📥 6.3K · ⏱️ 04.06.2019):
	```
	conda install -c conda-forge pygal
	```
</details>
<details><summary><b><a href="https://github.com/danielegrattarola/spektral">Spektral</a></b> (🥈22 ·  ⭐ 1.7K) - Graph Neural Networks with Keras and Tensorflow 2. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/danielegrattarola/spektral) (👨‍💻 16 · 🔀 220 · 📦 46 · 📋 140 - 15% open · ⏱️ 24.03.2021):

	```
	git clone https://github.com/danielegrattarola/spektral
	```
- [PyPi](https://pypi.org/project/spektral) (📥 3.5K / month):
	```
	pip install spektral
	```
</details>
<details><summary><b><a href="https://github.com/benedekrozemberczki/karateclub">Karate Club</a></b> (🥈22 ·  ⭐ 1.2K) - Karate Club: An API Oriented Open-source Python Framework for.. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/benedekrozemberczki/karateclub) (👨‍💻 11 · 🔀 140 · 📦 36 · 📋 54 - 7% open · ⏱️ 11.04.2021):

	```
	git clone https://github.com/benedekrozemberczki/karateclub
	```
- [PyPi](https://pypi.org/project/karateclub) (📥 8.6K / month):
	```
	pip install karateclub
	```
</details>
<details><summary><b><a href="https://github.com/Accenture/AmpliGraph">AmpliGraph</a></b> (🥈21 ·  ⭐ 1.5K · 💤) - Python library for Representation Learning on Knowledge.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/Accenture/AmpliGraph) (👨‍💻 14 · 🔀 160 · 📦 13 · 📋 180 - 12% open · ⏱️ 25.08.2020):

	```
	git clone https://github.com/Accenture/AmpliGraph
	```
- [PyPi](https://pypi.org/project/ampligraph) (📥 1.5K / month):
	```
	pip install ampligraph
	```
</details>
<details><summary><b><a href="https://github.com/rusty1s/pytorch_cluster">torch-cluster</a></b> (🥈20 ·  ⭐ 360) - PyTorch Extension Library of Optimized Graph Cluster.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rusty1s/pytorch_cluster) (👨‍💻 18 · 🔀 71 · 📋 79 - 48% open · ⏱️ 06.03.2021):

	```
	git clone https://github.com/rusty1s/pytorch_cluster
	```
- [PyPi](https://pypi.org/project/torch-cluster) (📥 9.8K / month):
	```
	pip install torch-cluster
	```
</details>
<details><summary><b><a href="https://github.com/pykeen/pykeen">PyKEEN</a></b> (🥉19 ·  ⭐ 390) - A Python library for learning and evaluating knowledge graph embeddings. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pykeen/pykeen) (👨‍💻 18 · 🔀 63 · 📥 79 · 📋 170 - 35% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/pykeen/pykeen
	```
- [PyPi](https://pypi.org/project/pykeen) (📥 820 / month):
	```
	pip install pykeen
	```
</details>
<details><summary><b><a href="https://github.com/phanein/deepwalk">DeepWalk</a></b> (🥉18 ·  ⭐ 2.2K · 💤) - DeepWalk - Deep Learning for Graphs. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/phanein/deepwalk) (👨‍💻 10 · 🔀 760 · 📦 36 · 📋 98 - 18% open · ⏱️ 02.04.2020):

	```
	git clone https://github.com/phanein/deepwalk
	```
- [PyPi](https://pypi.org/project/deepwalk) (📥 2.5K / month):
	```
	pip install deepwalk
	```
</details>
<details><summary><b><a href="https://github.com/PaddlePaddle/PGL">Paddle Graph Learning</a></b> (🥉18 ·  ⭐ 990 · 📉) - Paddle Graph Learning (PGL) is an efficient and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PaddlePaddle/PGL) (👨‍💻 16 · 🔀 140 · 📦 11 · 📋 57 - 35% open · ⏱️ 25.04.2021):

	```
	git clone https://github.com/PaddlePaddle/PGL
	```
- [PyPi](https://pypi.org/project/pgl) (📥 1.1K / month):
	```
	pip install pgl
	```
</details>
<details><summary><b><a href="https://github.com/benedekrozemberczki/pytorch_geometric_temporal">pytorch_geometric_temporal</a></b> (🥉18 ·  ⭐ 650) - A Temporal Extension Library for PyTorch Geometric. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/benedekrozemberczki/pytorch_geometric_temporal) (👨‍💻 9 · 🔀 81 · 📋 27 - 7% open · ⏱️ 25.04.2021):

	```
	git clone https://github.com/benedekrozemberczki/pytorch_geometric_temporal
	```
- [PyPi](https://pypi.org/project/torch-geometric-temporal) (📥 800 / month):
	```
	pip install torch-geometric-temporal
	```
</details>
<details><summary><b><a href="https://github.com/deepmind/graph_nets">graph-nets</a></b> (🥉16 ·  ⭐ 4.9K) - Build Graph Nets in Tensorflow. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deepmind/graph_nets) (👨‍💻 10 · 🔀 730 · 📋 120 - 6% open · ⏱️ 04.12.2020):

	```
	git clone https://github.com/deepmind/graph_nets
	```
- [PyPi](https://pypi.org/project/graph-nets) (📥 1.1K / month):
	```
	pip install graph-nets
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/PyTorch-BigGraph">PyTorch-BigGraph</a></b> (🥉16 ·  ⭐ 2.8K) - Generate embeddings from large-scale graph-structured.. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/PyTorch-BigGraph) (👨‍💻 20 · 🔀 370 · 📥 110 · 📋 140 - 25% open · ⏱️ 29.03.2021):

	```
	git clone https://github.com/facebookresearch/PyTorch-BigGraph
	```
- [PyPi](https://pypi.org/project/torchbiggraph) (📥 790 / month):
	```
	pip install torchbiggraph
	```
</details>
<details><summary><b><a href="https://github.com/alibaba/euler">Euler</a></b> (🥉16 ·  ⭐ 2.5K · 💤) - A distributed graph deep learning framework. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/alibaba/euler) (👨‍💻 3 · 🔀 510 · 📋 310 - 67% open · ⏱️ 29.07.2020):

	```
	git clone https://github.com/alibaba/euler
	```
- [PyPi](https://pypi.org/project/euler-gl) (📥 28 / month):
	```
	pip install euler-gl
	```
</details>
<details><summary><b><a href="https://github.com/vaticle/kglib">kglib</a></b> (🥉16 ·  ⭐ 420) - Grakn Knowledge Graph Library (ML R&D). <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/vaticle/kglib) (👨‍💻 7 · 🔀 77 · 📥 210 · 📋 57 - 14% open · ⏱️ 15.01.2021):

	```
	git clone https://github.com/graknlabs/kglib
	```
- [PyPi](https://pypi.org/project/grakn-kglib) (📥 150 / month):
	```
	pip install grakn-kglib
	```
</details>
<details><summary><b><a href="https://github.com/IBCNServices/pyRDF2Vec">pyRDF2Vec</a></b> (🥉16 ·  ⭐ 100) - Python Implementation and Extension of RDF2Vec. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/IBCNServices/pyRDF2Vec) (👨‍💻 5 · 🔀 19 · 📋 35 - 5% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/IBCNServices/pyRDF2Vec
	```
- [PyPi](https://pypi.org/project/pyrdf2vec) (📥 320 / month):
	```
	pip install pyrdf2vec
	```
</details>
<details><summary><b><a href="https://github.com/shenweichen/GraphEmbedding">GraphEmbedding</a></b> (🥉15 ·  ⭐ 1.9K) - Implementation and experiments of graph embedding algorithms. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/shenweichen/GraphEmbedding) (👨‍💻 8 · 🔀 580 · 📦 7 · 📋 41 - 68% open · ⏱️ 18.10.2020):

	```
	git clone https://github.com/shenweichen/GraphEmbedding
	```
</details>
<details><summary><b><a href="https://github.com/gsi-upm/sematch">Sematch</a></b> (🥉15 ·  ⭐ 350 · 💀) - semantic similarity framework for knowledge graph. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/gsi-upm/sematch) (👨‍💻 5 · 🔀 98 · 📦 28 · 📋 28 - 32% open · ⏱️ 27.03.2019):

	```
	git clone https://github.com/gsi-upm/sematch
	```
- [PyPi](https://pypi.org/project/sematch) (📥 190 / month):
	```
	pip install sematch
	```
</details>
<details><summary><b><a href="https://github.com/williamleif/GraphSAGE">GraphSAGE</a></b> (🥉14 ·  ⭐ 2.3K · 💀) - Representation learning on large graphs using stochastic.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/williamleif/GraphSAGE) (👨‍💻 9 · 🔀 640 · 📋 140 - 57% open · ⏱️ 19.09.2018):

	```
	git clone https://github.com/williamleif/GraphSAGE
	```
</details>
<details><summary><b><a href="https://github.com/thunlp/OpenNE">OpenNE</a></b> (🥉14 ·  ⭐ 1.4K · 💀) - An Open-Source Package for Network Embedding (NE). <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/thunlp/OpenNE) (👨‍💻 10 · 🔀 450 · 📋 90 - 8% open · ⏱️ 12.08.2019):

	```
	git clone https://github.com/thunlp/OpenNE
	```
</details>
<details><summary><b><a href="https://github.com/THUMNLab/AutoGL">AutoGL</a></b> (🥉14 ·  ⭐ 630 · 🐣) - An autoML framework & toolkit for machine learning on graphs. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/THUMNLab/AutoGL) (👨‍💻 5 · 🔀 63 · 📋 7 - 42% open · ⏱️ 10.04.2021):

	```
	git clone https://github.com/THUMNLab/AutoGL
	```
- [PyPi](https://pypi.org/project/auto-graph-learning) (📥 94 / month):
	```
	pip install auto-graph-learning
	```
</details>
<details><summary><b><a href="https://github.com/deepgraph/deepgraph">DeepGraph</a></b> (🥉14 ·  ⭐ 230) - Analyze Data with Pandas-based Networks. Documentation:. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deepgraph/deepgraph) (👨‍💻 2 · 🔀 34 · 📦 1 · 📋 12 - 58% open · ⏱️ 01.10.2020):

	```
	git clone https://github.com/deepgraph/deepgraph
	```
- [PyPi](https://pypi.org/project/deepgraph) (📥 450 / month):
	```
	pip install deepgraph
	```
- [Conda](https://anaconda.org/conda-forge/deepgraph) (📥 91K · ⏱️ 15.01.2021):
	```
	conda install -c conda-forge deepgraph
	```
</details>
<details><summary><b><a href="https://github.com/DeepGraphLearning/graphvite">GraphVite</a></b> (🥉13 ·  ⭐ 890) - GraphVite: A General and High-performance Graph Embedding System. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/DeepGraphLearning/graphvite) (🔀 120 · 📋 84 - 34% open · ⏱️ 14.01.2021):

	```
	git clone https://github.com/DeepGraphLearning/graphvite
	```
- [Conda](https://anaconda.org/milagraph/graphvite) (📥 3.7K · ⏱️ 19.03.2020):
	```
	conda install -c milagraph graphvite
	```
</details>
<details><summary><b><a href="https://github.com/thunlp/OpenKE">OpenKE</a></b> (🥉12 ·  ⭐ 2.5K) - An Open-Source Package for Knowledge Embedding (KE). <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/thunlp/OpenKE) (👨‍💻 10 · 🔀 780 · 📋 290 - 21% open · ⏱️ 06.04.2021):

	```
	git clone https://github.com/thunlp/OpenKE
	```
</details>
<br>

## Audio Data

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for audio analysis, manipulation, transformation, and extraction, as well as speech recognition and music generation tasks._

<details><summary><b><a href="https://github.com/mozilla/DeepSpeech">DeepSpeech</a></b> (🥇31 ·  ⭐ 17K) - DeepSpeech is an open source embedded (offline, on-.. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/mozilla/DeepSpeech) (👨‍💻 160 · 🔀 3K · 📥 520K · 📦 460 · 📋 2K - 4% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/mozilla/DeepSpeech
	```
- [PyPi](https://pypi.org/project/deepspeech) (📥 19K / month):
	```
	pip install deepspeech
	```
</details>
<details><summary><b><a href="https://github.com/jiaaro/pydub">Pydub</a></b> (🥇31 ·  ⭐ 5.3K) - Manipulate audio with a simple and easy high level interface. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jiaaro/pydub) (👨‍💻 90 · 🔀 700 · 📦 6.8K · 📋 420 - 41% open · ⏱️ 21.04.2021):

	```
	git clone https://github.com/jiaaro/pydub
	```
- [PyPi](https://pypi.org/project/pydub) (📥 750K / month):
	```
	pip install pydub
	```
- [Conda](https://anaconda.org/conda-forge/pydub) (📥 15K · ⏱️ 13.03.2021):
	```
	conda install -c conda-forge pydub
	```
</details>
<details><summary><b><a href="https://github.com/magenta/magenta">Magenta</a></b> (🥇29 ·  ⭐ 17K) - Magenta: Music and Art Generation with Machine Intelligence. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/magenta/magenta) (👨‍💻 150 · 🔀 3.3K · 📦 290 · 📋 820 - 33% open · ⏱️ 19.04.2021):

	```
	git clone https://github.com/magenta/magenta
	```
- [PyPi](https://pypi.org/project/magenta) (📥 6.2K / month):
	```
	pip install magenta
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/audio">torchaudio</a></b> (🥇29 ·  ⭐ 1.3K) - Data manipulation and transformation for audio signal.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/audio) (👨‍💻 120 · 🔀 300 · 📦 2.6K · 📋 420 - 26% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/pytorch/audio
	```
- [PyPi](https://pypi.org/project/torchaudio) (📥 210K / month):
	```
	pip install torchaudio
	```
</details>
<details><summary><b><a href="https://github.com/Uberi/speech_recognition">SpeechRecognition</a></b> (🥈28 ·  ⭐ 5.6K · 💀) - Speech recognition module for Python, supporting.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/Uberi/speech_recognition) (👨‍💻 41 · 🔀 1.8K · 📦 7.9K · 📋 470 - 42% open · ⏱️ 02.07.2019):

	```
	git clone https://github.com/Uberi/speech_recognition
	```
- [PyPi](https://pypi.org/project/SpeechRecognition) (📥 150K / month):
	```
	pip install SpeechRecognition
	```
- [Conda](https://anaconda.org/conda-forge/speechrecognition) (📥 110K · ⏱️ 11.01.2021):
	```
	conda install -c conda-forge speechrecognition
	```
</details>
<details><summary><b><a href="https://github.com/librosa/librosa">librosa</a></b> (🥈28 ·  ⭐ 4.4K) - Python library for audio and music analysis. <code><a href="http://bit.ly/3hkKRql">ISC</a></code></summary>

- [GitHub](https://github.com/librosa/librosa) (👨‍💻 84 · 🔀 710 · 📦 11K · 📋 860 - 7% open · ⏱️ 14.04.2021):

	```
	git clone https://github.com/librosa/librosa
	```
- [PyPi](https://pypi.org/project/librosa) (📥 530K / month):
	```
	pip install librosa
	```
- [Conda](https://anaconda.org/conda-forge/librosa) (📥 270K · ⏱️ 22.07.2020):
	```
	conda install -c conda-forge librosa
	```
</details>
<details><summary><b><a href="https://github.com/aubio/aubio">aubio</a></b> (🥈26 ·  ⭐ 2.1K) - a library for audio and music analysis. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/aubio/aubio) (👨‍💻 24 · 🔀 300 · 📦 220 · 📋 280 - 38% open · ⏱️ 19.01.2021):

	```
	git clone https://github.com/aubio/aubio
	```
- [PyPi](https://pypi.org/project/aubio) (📥 2.5K / month):
	```
	pip install aubio
	```
- [Conda](https://anaconda.org/conda-forge/aubio) (📥 420K · ⏱️ 19.01.2021):
	```
	conda install -c conda-forge aubio
	```
</details>
<details><summary><b><a href="https://github.com/beetbox/audioread">audioread</a></b> (🥈26 ·  ⭐ 360) - cross-library (GStreamer + Core Audio + MAD + FFmpeg) audio decoding.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/beetbox/audioread) (👨‍💻 20 · 🔀 82 · 📦 4.8K · 📋 70 - 37% open · ⏱️ 20.10.2020):

	```
	git clone https://github.com/beetbox/audioread
	```
- [PyPi](https://pypi.org/project/audioread) (📥 520K / month):
	```
	pip install audioread
	```
- [Conda](https://anaconda.org/conda-forge/audioread) (📥 220K · ⏱️ 16.03.2021):
	```
	conda install -c conda-forge audioread
	```
</details>
<details><summary><b><a href="https://github.com/espnet/espnet">espnet</a></b> (🥈25 ·  ⭐ 3.7K) - End-to-End Speech Processing Toolkit. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/espnet/espnet) (👨‍💻 150 · 🔀 1.1K · 📥 61 · 📦 7 · 📋 1.3K - 11% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/espnet/espnet
	```
- [PyPi](https://pypi.org/project/espnet) (📥 2.4K / month):
	```
	pip install espnet
	```
</details>
<details><summary><b><a href="https://github.com/bastibe/python-soundfile">python-soundfile</a></b> (🥈25 ·  ⭐ 380) - SoundFile is an audio library based on libsndfile, CFFI, and.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/bastibe/python-soundfile) (👨‍💻 19 · 🔀 43 · 📥 2.3K · 📦 6.6K · 📋 140 - 37% open · ⏱️ 01.12.2020):

	```
	git clone https://github.com/bastibe/python-soundfile
	```
- [PyPi](https://pypi.org/project/soundfile) (📥 670K / month):
	```
	pip install soundfile
	```
</details>
<details><summary><b><a href="https://github.com/deezer/spleeter">spleeter</a></b> (🥉24 ·  ⭐ 16K) - Deezer source separation library including pretrained models. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deezer/spleeter) (👨‍💻 17 · 🔀 1.7K · 📥 1M · 📋 540 - 15% open · ⏱️ 15.04.2021):

	```
	git clone https://github.com/deezer/spleeter
	```
- [PyPi](https://pypi.org/project/spleeter) (📥 11K / month):
	```
	pip install spleeter
	```
- [Conda](https://anaconda.org/conda-forge/spleeter) (📥 50K · ⏱️ 30.06.2020):
	```
	conda install -c conda-forge spleeter
	```
</details>
<details><summary><b><a href="https://github.com/tyiannak/pyAudioAnalysis">pyAudioAnalysis</a></b> (🥉24 ·  ⭐ 3.9K) - Python Audio Analysis Library: Feature Extraction,.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/tyiannak/pyAudioAnalysis) (👨‍💻 23 · 🔀 960 · 📦 200 · 📋 260 - 59% open · ⏱️ 20.04.2021):

	```
	git clone https://github.com/tyiannak/pyAudioAnalysis
	```
- [PyPi](https://pypi.org/project/pyAudioAnalysis) (📥 15K / month):
	```
	pip install pyAudioAnalysis
	```
</details>
<details><summary><b><a href="https://github.com/magenta/ddsp">DDSP</a></b> (🥉24 ·  ⭐ 1.8K) - DDSP: Differentiable Digital Signal Processing. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/magenta/ddsp) (👨‍💻 25 · 🔀 180 · 📦 11 · 📋 110 - 11% open · ⏱️ 08.04.2021):

	```
	git clone https://github.com/magenta/ddsp
	```
- [PyPi](https://pypi.org/project/ddsp) (📥 2.1K / month):
	```
	pip install ddsp
	```
</details>
<details><summary><b><a href="https://github.com/MTG/essentia">Essentia</a></b> (🥉23 ·  ⭐ 1.8K) - C++ library for audio and music analysis, description and.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/MTG/essentia) (👨‍💻 71 · 🔀 410 · 📦 180 · 📋 870 - 33% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/MTG/essentia
	```
- [PyPi](https://pypi.org/project/essentia) (📥 4.2K / month):
	```
	pip install essentia
	```
</details>
<details><summary><b><a href="https://github.com/Picovoice/porcupine">Porcupine</a></b> (🥉22 ·  ⭐ 2.4K) - On-device wake word detection powered by deep learning. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Picovoice/porcupine) (👨‍💻 26 · 🔀 340 · 📦 5 · 📋 300 - 2% open · ⏱️ 22.04.2021):

	```
	git clone https://github.com/Picovoice/Porcupine
	```
- [PyPi](https://pypi.org/project/pvporcupine) (📥 1.6K / month):
	```
	pip install pvporcupine
	```
</details>
<details><summary><b><a href="https://github.com/keunwoochoi/kapre">kapre</a></b> (🥉22 ·  ⭐ 730) - kapre: Keras Audio Preprocessors. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/keunwoochoi/kapre) (👨‍💻 13 · 🔀 130 · 📥 10 · 📦 690 · 📋 86 - 6% open · ⏱️ 25.03.2021):

	```
	git clone https://github.com/keunwoochoi/kapre
	```
- [PyPi](https://pypi.org/project/kapre) (📥 2.4K / month):
	```
	pip install kapre
	```
</details>
<details><summary><b><a href="https://github.com/mozilla/TTS">TTS</a></b> (🥉21 ·  ⭐ 4.6K) - Deep learning for Text to Speech (Discussion forum:.. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code></summary>

- [GitHub](https://github.com/mozilla/TTS) (👨‍💻 55 · 🔀 730 · 📥 520 · 📋 490 - 6% open · ⏱️ 12.02.2021):

	```
	git clone https://github.com/mozilla/TTS
	```
</details>
<details><summary><b><a href="https://github.com/jameslyons/python_speech_features">python_speech_features</a></b> (🥉20 ·  ⭐ 1.9K) - This library provides common speech features for ASR.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jameslyons/python_speech_features) (👨‍💻 18 · 🔀 550 · 📋 68 - 27% open · ⏱️ 31.12.2020):

	```
	git clone https://github.com/jameslyons/python_speech_features
	```
- [PyPi](https://pypi.org/project/python_speech_features) (📥 83K / month):
	```
	pip install python_speech_features
	```
</details>
<details><summary><b><a href="https://github.com/devsnd/tinytag">tinytag</a></b> (🥉20 ·  ⭐ 450) - Read music meta data and length of MP3, OGG, OPUS, MP4, M4A, FLAC, WMA and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/devsnd/tinytag) (👨‍💻 18 · 🔀 77 · 📦 340 · 📋 75 - 14% open · ⏱️ 28.03.2021):

	```
	git clone https://github.com/devsnd/tinytag
	```
- [PyPi](https://pypi.org/project/tinytag) (📥 5.3K / month):
	```
	pip install tinytag
	```
</details>
<details><summary><b><a href="https://github.com/worldveil/dejavu">Dejavu</a></b> (🥉19 ·  ⭐ 5.4K · 💤) - Audio fingerprinting and recognition in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/worldveil/dejavu) (👨‍💻 23 · 🔀 1.2K · 📦 18 · 📋 190 - 33% open · ⏱️ 03.06.2020):

	```
	git clone https://github.com/worldveil/dejavu
	```
- [PyPi](https://pypi.org/project/PyDejavu) (📥 180 / month):
	```
	pip install PyDejavu
	```
</details>
<details><summary><b><a href="https://github.com/CPJKU/madmom">Madmom</a></b> (🥉19 ·  ⭐ 740 · 💀) - Python audio and music signal processing library. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/CPJKU/madmom) (👨‍💻 19 · 🔀 120 · 📦 120 · 📋 230 - 20% open · ⏱️ 19.12.2019):

	```
	git clone https://github.com/CPJKU/madmom
	```
- [PyPi](https://pypi.org/project/madmom) (📥 2.5K / month):
	```
	pip install madmom
	```
</details>
<details><summary><b><a href="https://github.com/bmcfee/muda">Muda</a></b> (🥉17 ·  ⭐ 180 · 💤) - A library for augmenting annotated audio data. <code><a href="http://bit.ly/3hkKRql">ISC</a></code></summary>

- [GitHub](https://github.com/bmcfee/muda) (👨‍💻 6 · 🔀 32 · 📦 9 · 📋 49 - 10% open · ⏱️ 20.07.2020):

	```
	git clone https://github.com/bmcfee/muda
	```
- [PyPi](https://pypi.org/project/muda) (📥 280 / month):
	```
	pip install muda
	```
</details>
<details><summary><b><a href="https://github.com/adefossez/julius">Julius</a></b> (🥉13 ·  ⭐ 180 · 🐣) - Fast PyTorch based DSP for audio and 1D signals. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/adefossez/julius) (👨‍💻 2 · 🔀 6 · 📦 9 · ⏱️ 26.04.2021):

	```
	git clone https://github.com/adefossez/julius
	```
- [PyPi](https://pypi.org/project/julius) (📥 2.5K / month):
	```
	pip install julius
	```
</details>
<br>

## Geospatial Data

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries to load, process, analyze, and write geographic data as well as libraries for spatial analysis, map visualization, and geocoding._

<details><summary><b><a href="https://github.com/geopy/geopy">geopy</a></b> (🥇33 ·  ⭐ 3.3K) - Geocoding library for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/geopy/geopy) (👨‍💻 120 · 🔀 530 · 📦 20K · 📋 240 - 7% open · ⏱️ 17.04.2021):

	```
	git clone https://github.com/geopy/geopy
	```
- [PyPi](https://pypi.org/project/geopy) (📥 4.5M / month):
	```
	pip install geopy
	```
- [Conda](https://anaconda.org/conda-forge/geopy) (📥 540K · ⏱️ 27.12.2020):
	```
	conda install -c conda-forge geopy
	```
</details>
<details><summary><b><a href="https://github.com/visgl/deck.gl">pydeck</a></b> (🥇32 ·  ⭐ 8.6K) - WebGL2 powered geospatial visualization layers. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/visgl/deck.gl) (👨‍💻 160 · 🔀 1.5K · 📦 1.5K · 📋 2.1K - 3% open · ⏱️ 20.04.2021):

	```
	git clone https://github.com/visgl/deck.gl
	```
- [PyPi](https://pypi.org/project/pydeck) (📥 220K / month):
	```
	pip install pydeck
	```
- [Conda](https://anaconda.org/conda-forge/pydeck) (📥 27K · ⏱️ 13.04.2021):
	```
	conda install -c conda-forge pydeck
	```
- [NPM](https://www.npmjs.com/package/deck.gl) (📥 220K / month):
	```
	npm install deck.gl
	```
</details>
<details><summary><b><a href="https://github.com/python-visualization/folium">folium</a></b> (🥇32 ·  ⭐ 5.2K) - Python Data. Leaflet.js Maps. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/python-visualization/folium) (👨‍💻 120 · 🔀 1.9K · 📦 9.6K · 📋 830 - 16% open · ⏱️ 09.03.2021):

	```
	git clone https://github.com/python-visualization/folium
	```
- [PyPi](https://pypi.org/project/folium) (📥 420K / month):
	```
	pip install folium
	```
- [Conda](https://anaconda.org/conda-forge/folium) (📥 350K · ⏱️ 12.03.2021):
	```
	conda install -c conda-forge folium
	```
</details>
<details><summary><b><a href="https://github.com/geopandas/geopandas">GeoPandas</a></b> (🥇32 ·  ⭐ 2.6K) - Python tools for geographic data. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/geopandas/geopandas) (👨‍💻 140 · 🔀 560 · 📥 990 · 📦 8.2K · 📋 1K - 27% open · ⏱️ 22.04.2021):

	```
	git clone https://github.com/geopandas/geopandas
	```
- [PyPi](https://pypi.org/project/geopandas) (📥 1M / month):
	```
	pip install geopandas
	```
- [Conda](https://anaconda.org/conda-forge/geopandas) (📥 960K · ⏱️ 01.03.2021):
	```
	conda install -c conda-forge geopandas
	```
</details>
<details><summary><b><a href="https://github.com/pyproj4/pyproj">pyproj</a></b> (🥈31 ·  ⭐ 600) - Python interface to PROJ (cartographic projections and coordinate.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pyproj4/pyproj) (👨‍💻 40 · 🔀 150 · 📦 9.4K · 📋 400 - 1% open · ⏱️ 11.04.2021):

	```
	git clone https://github.com/pyproj4/pyproj
	```
- [PyPi](https://pypi.org/project/pyproj) (📥 2.4M / month):
	```
	pip install pyproj
	```
- [Conda](https://anaconda.org/conda-forge/pyproj) (📥 2.1M · ⏱️ 05.03.2021):
	```
	conda install -c conda-forge pyproj
	```
</details>
<details><summary><b><a href="https://github.com/Toblerity/Shapely">Shapely</a></b> (🥈30 ·  ⭐ 2.2K) - Manipulation and analysis of geometric objects. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/Toblerity/Shapely) (👨‍💻 110 · 🔀 400 · 📦 18K · 📋 740 - 16% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/Toblerity/Shapely
	```
- [PyPi](https://pypi.org/project/shapely) (📥 4M / month):
	```
	pip install shapely
	```
- [Conda](https://anaconda.org/conda-forge/shapely) (📥 2.3M · ⏱️ 05.03.2021):
	```
	conda install -c conda-forge shapely
	```
</details>
<details><summary><b><a href="https://github.com/DenisCarriere/geocoder">Geocoder</a></b> (🥈29 ·  ⭐ 1.3K · 💀) - Python Geocoder. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/DenisCarriere/geocoder) (👨‍💻 74 · 🔀 250 · 📦 3.3K · 📋 280 - 23% open · ⏱️ 12.10.2018):

	```
	git clone https://github.com/DenisCarriere/geocoder
	```
- [PyPi](https://pypi.org/project/geocoder) (📥 1.2M / month):
	```
	pip install geocoder
	```
- [Conda](https://anaconda.org/conda-forge/geocoder) (📥 89K · ⏱️ 27.06.2019):
	```
	conda install -c conda-forge geocoder
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-widgets/ipyleaflet">ipyleaflet</a></b> (🥈28 ·  ⭐ 1.1K) - A Jupyter - Leaflet.js bridge. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/jupyter-widgets/ipyleaflet) (👨‍💻 64 · 🔀 270 · 📦 820 · 📋 410 - 37% open · ⏱️ 12.04.2021):

	```
	git clone https://github.com/jupyter-widgets/ipyleaflet
	```
- [PyPi](https://pypi.org/project/ipyleaflet) (📥 38K / month):
	```
	pip install ipyleaflet
	```
- [Conda](https://anaconda.org/conda-forge/ipyleaflet) (📥 660K · ⏱️ 16.01.2021):
	```
	conda install -c conda-forge ipyleaflet
	```
- [NPM](https://www.npmjs.com/package/jupyter-leaflet) (📥 21K / month):
	```
	npm install jupyter-leaflet
	```
</details>
<details><summary><b><a href="https://github.com/mapbox/rasterio">Rasterio</a></b> (🥈27 ·  ⭐ 1.5K) - Rasterio reads and writes geospatial raster datasets. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/mapbox/rasterio) (👨‍💻 110 · 🔀 390 · 📥 700 · 📦 3.1K · 📋 1.4K - 9% open · ⏱️ 20.04.2021):

	```
	git clone https://github.com/mapbox/rasterio
	```
- [PyPi](https://pypi.org/project/rasterio) (📥 450K / month):
	```
	pip install rasterio
	```
- [Conda](https://anaconda.org/conda-forge/rasterio) (📥 1M · ⏱️ 07.04.2021):
	```
	conda install -c conda-forge rasterio
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/geojson">geojson</a></b> (🥈27 ·  ⭐ 620) - Python bindings and utilities for GeoJSON. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jazzband/geojson) (👨‍💻 44 · 🔀 85 · 📦 6.4K · 📋 72 - 27% open · ⏱️ 21.03.2021):

	```
	git clone https://github.com/jazzband/geojson
	```
- [PyPi](https://pypi.org/project/geojson) (📥 660K / month):
	```
	pip install geojson
	```
- [Conda](https://anaconda.org/conda-forge/geojson) (📥 390K · ⏱️ 11.08.2019):
	```
	conda install -c conda-forge geojson
	```
</details>
<details><summary><b><a href="https://github.com/mapbox/rasterio">Cartopy</a></b> (🥉26 ·  ⭐ 1.5K) - Rasterio reads and writes geospatial raster datasets. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/mapbox/rasterio) (👨‍💻 110 · 🔀 390 · 📥 700 · 📦 3.1K · 📋 1.4K - 9% open · ⏱️ 20.04.2021):

	```
	git clone https://github.com/mapbox/rasterio
	```
- [PyPi](https://pypi.org/project/Cartopy) (📥 62K / month):
	```
	pip install Cartopy
	```
- [Conda](https://anaconda.org/conda-forge/cartopy) (📥 1.5M · ⏱️ 23.04.2021):
	```
	conda install -c conda-forge cartopy
	```
</details>
<details><summary><b><a href="https://github.com/Toblerity/Fiona">Fiona</a></b> (🥉26 ·  ⭐ 800) - Fiona reads and writes geographic data files. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/Toblerity/Fiona) (👨‍💻 65 · 🔀 160 · 📦 5.6K · 📋 620 - 10% open · ⏱️ 25.04.2021):

	```
	git clone https://github.com/Toblerity/Fiona
	```
- [PyPi](https://pypi.org/project/fiona) (📥 1.3M / month):
	```
	pip install fiona
	```
- [Conda](https://anaconda.org/conda-forge/fiona) (📥 1.9M · ⏱️ 08.04.2021):
	```
	conda install -c conda-forge fiona
	```
</details>
<details><summary><b><a href="https://github.com/pytroll/satpy">Satpy</a></b> (🥉24 ·  ⭐ 690) - Python package for earth-observing satellite data processing. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/pytroll/satpy) (👨‍💻 110 · 🔀 190 · 📦 41 · 📋 570 - 43% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/pytroll/satpy
	```
- [PyPi](https://pypi.org/project/satpy) (📥 1.4K / month):
	```
	pip install satpy
	```
- [Conda](https://anaconda.org/conda-forge/satpy) (📥 60K · ⏱️ 26.03.2021):
	```
	conda install -c conda-forge satpy
	```
</details>
<details><summary><b><a href="https://github.com/Esri/arcgis-python-api">ArcGIS API</a></b> (🥉23 ·  ⭐ 1K) - Documentation and samples for ArcGIS API for Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Esri/arcgis-python-api) (👨‍💻 62 · 🔀 720 · 📋 330 - 32% open · ⏱️ 19.04.2021):

	```
	git clone https://github.com/Esri/arcgis-python-api
	```
- [PyPi](https://pypi.org/project/arcgis) (📥 37K / month):
	```
	pip install arcgis
	```
- [Docker Hub](https://hub.docker.com/r/esridocker/arcgis-api-python-notebook) (📥 4.3K · ⭐ 32 · ⏱️ 06.03.2020):
	```
	docker pull esridocker/arcgis-api-python-notebook
	```
</details>
<details><summary><b><a href="https://github.com/pysal/pysal">PySAL</a></b> (🥉23 ·  ⭐ 840) - PySAL: Python Spatial Analysis Library Meta-Package. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/pysal/pysal) (👨‍💻 71 · 🔀 240 · 📋 590 - 1% open · ⏱️ 01.02.2021):

	```
	git clone https://github.com/pysal/pysal
	```
- [PyPi](https://pypi.org/project/pysal) (📥 15K / month):
	```
	pip install pysal
	```
- [Conda](https://anaconda.org/conda-forge/pysal) (📥 410K · ⏱️ 08.02.2021):
	```
	conda install -c conda-forge pysal
	```
</details>
<details><summary><b><a href="https://github.com/mapbox/mapboxgl-jupyter">Mapbox GL</a></b> (🥉23 ·  ⭐ 560) - Use Mapbox GL JS to visualize data in a Python Jupyter notebook. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/mapbox/mapboxgl-jupyter) (👨‍💻 21 · 🔀 120 · 📦 99 · 📋 95 - 29% open · ⏱️ 19.04.2021):

	```
	git clone https://github.com/mapbox/mapboxgl-jupyter
	```
- [PyPi](https://pypi.org/project/mapboxgl) (📥 8.1K / month):
	```
	pip install mapboxgl
	```
</details>
<details><summary><b><a href="https://github.com/holoviz/geoviews">GeoViews</a></b> (🥉21 ·  ⭐ 340) - Simple, concise geographical visualization in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/holoviz/geoviews) (👨‍💻 23 · 🔀 63 · 📋 260 - 30% open · ⏱️ 13.04.2021):

	```
	git clone https://github.com/holoviz/geoviews
	```
- [PyPi](https://pypi.org/project/geoviews) (📥 7.2K / month):
	```
	pip install geoviews
	```
- [Conda](https://anaconda.org/conda-forge/geoviews) (📥 66K · ⏱️ 14.03.2021):
	```
	conda install -c conda-forge geoviews
	```
</details>
<details><summary><b><a href="https://github.com/sentinelsat/sentinelsat">Sentinelsat</a></b> (🥉20 ·  ⭐ 590) - Search and download Copernicus Sentinel satellite images. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/sentinelsat/sentinelsat) (👨‍💻 36 · 🔀 160 · 📥 200 · 📦 190 · 📋 250 - 13% open · ⏱️ 17.04.2021):

	```
	git clone https://github.com/sentinelsat/sentinelsat
	```
- [PyPi](https://pypi.org/project/sentinelsat) (📥 19K / month):
	```
	pip install sentinelsat
	```
</details>
<details><summary><b><a href="https://github.com/earthlab/earthpy">EarthPy</a></b> (🥉19 ·  ⭐ 250) - A package built to support working with spatial data using open source.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/earthlab/earthpy) (👨‍💻 39 · 🔀 110 · 📦 88 · 📋 220 - 7% open · ⏱️ 06.04.2021):

	```
	git clone https://github.com/earthlab/earthpy
	```
- [PyPi](https://pypi.org/project/earthpy) (📥 3K / month):
	```
	pip install earthpy
	```
- [Conda](https://anaconda.org/conda-forge/earthpy) (📥 31K · ⏱️ 19.06.2020):
	```
	conda install -c conda-forge earthpy
	```
</details>
<details><summary><b><a href="https://github.com/andrea-cuttone/geoplotlib">geoplotlib</a></b> (🥉18 ·  ⭐ 910 · 💀) - python toolbox for visualizing geographical data and making maps. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/andrea-cuttone/geoplotlib) (👨‍💻 8 · 🔀 150 · 📦 94 · 📋 42 - 57% open · ⏱️ 06.05.2019):

	```
	git clone https://github.com/andrea-cuttone/geoplotlib
	```
- [PyPi](https://pypi.org/project/geoplotlib) (📥 2.1K / month):
	```
	pip install geoplotlib
	```
</details>
<details><summary><b><a href="https://github.com/pbugnion/gmaps">gmaps</a></b> (🥉18 ·  ⭐ 710 · 💀) - Google maps for Jupyter notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pbugnion/gmaps) (👨‍💻 16 · 🔀 140 · 📦 1 · 📋 200 - 31% open · ⏱️ 22.07.2019):

	```
	git clone https://github.com/pbugnion/gmaps
	```
- [PyPi](https://pypi.org/project/gmaps) (📥 9.8K / month):
	```
	pip install gmaps
	```
- [Conda](https://anaconda.org/conda-forge/gmaps) (📥 220K · ⏱️ 02.08.2019):
	```
	conda install -c conda-forge gmaps
	```
- [NPM](https://www.npmjs.com/package/jupyter-gmaps) (📥 2.1K / month):
	```
	npm install jupyter-gmaps
	```
</details>
<details><summary><b><a href="https://github.com/geospace-code/pymap3d">pymap3d</a></b> (🥉18 ·  ⭐ 180) - pure-Python (Numpy optional) 3D coordinate conversions for geospace ecef.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/geospace-code/pymap3d) (👨‍💻 8 · 🔀 57 · 📋 26 - 7% open · ⏱️ 13.04.2021):

	```
	git clone https://github.com/geospace-code/pymap3d
	```
- [PyPi](https://pypi.org/project/pymap3d) (📥 41K / month):
	```
	pip install pymap3d
	```
- [Conda](https://anaconda.org/conda-forge/pymap3d) (📥 8.7K · ⏱️ 13.04.2021):
	```
	conda install -c conda-forge pymap3d
	```
</details>
<br>

## Financial Data

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for algorithmic stock/crypto trading, risk analytics, backtesting, technical analysis, and other tasks on financial data._

<details><summary><b><a href="https://github.com/quantopian/zipline">zipline</a></b> (🥇29 ·  ⭐ 14K) - Zipline, a Pythonic Algorithmic Trading Library. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/quantopian/zipline) (👨‍💻 150 · 🔀 3.7K · 📦 710 · 📋 950 - 31% open · ⏱️ 14.10.2020):

	```
	git clone https://github.com/quantopian/zipline
	```
- [PyPi](https://pypi.org/project/zipline) (📥 6.9K / month):
	```
	pip install zipline
	```
</details>
<details><summary><b><a href="https://github.com/ranaroussi/yfinance">yfinance</a></b> (🥇28 ·  ⭐ 4.9K) - Yahoo! Finance market data downloader (+faster Pandas Datareader). <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/ranaroussi/yfinance) (👨‍💻 36 · 🔀 1.2K · 📦 4.1K · 📋 520 - 56% open · ⏱️ 25.03.2021):

	```
	git clone https://github.com/ranaroussi/yfinance
	```
- [PyPi](https://pypi.org/project/yfinance) (📥 200K / month):
	```
	pip install yfinance
	```
- [Conda](https://anaconda.org/ranaroussi/yfinance) (📥 44K · ⏱️ 27.12.2019):
	```
	conda install -c ranaroussi yfinance
	```
</details>
<details><summary><b><a href="https://github.com/quantopian/pyfolio">pyfolio</a></b> (🥇28 ·  ⭐ 3.7K · 💤) - Portfolio and risk analytics in Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/quantopian/pyfolio) (👨‍💻 55 · 🔀 1.1K · 📦 230 · 📋 390 - 31% open · ⏱️ 15.07.2020):

	```
	git clone https://github.com/quantopian/pyfolio
	```
- [PyPi](https://pypi.org/project/pyfolio) (📥 8.5K / month):
	```
	pip install pyfolio
	```
- [Conda](https://anaconda.org/conda-forge/pyfolio) (📥 6.2K · ⏱️ 16.05.2020):
	```
	conda install -c conda-forge pyfolio
	```
</details>
<details><summary><b><a href="https://github.com/mementum/backtrader">backtrader</a></b> (🥈25 ·  ⭐ 6.3K) - Python Backtesting library for trading strategies. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/mementum/backtrader) (👨‍💻 51 · 🔀 1.9K · 📦 540 · ⏱️ 11.02.2021):

	```
	git clone https://github.com/mementum/backtrader
	```
- [PyPi](https://pypi.org/project/backtrader) (📥 34K / month):
	```
	pip install backtrader
	```
</details>
<details><summary><b><a href="https://github.com/bukosabino/ta">ta</a></b> (🥈25 ·  ⭐ 2.1K) - Technical Analysis Library using Pandas and Numpy. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/bukosabino/ta) (👨‍💻 23 · 🔀 510 · 📦 520 · 📋 160 - 46% open · ⏱️ 29.11.2020):

	```
	git clone https://github.com/bukosabino/ta
	```
- [PyPi](https://pypi.org/project/ta) (📥 72K / month):
	```
	pip install ta
	```
</details>
<details><summary><b><a href="https://github.com/pmorissette/bt">bt</a></b> (🥈25 ·  ⭐ 1K) - bt - flexible backtesting for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pmorissette/bt) (👨‍💻 21 · 🔀 270 · 📦 51 · 📋 230 - 11% open · ⏱️ 24.04.2021):

	```
	git clone https://github.com/pmorissette/bt
	```
- [PyPi](https://pypi.org/project/bt) (📥 9K / month):
	```
	pip install bt
	```
</details>
<details><summary><b><a href="https://github.com/pmorissette/ffn">ffn</a></b> (🥈25 ·  ⭐ 840) - ffn - a financial function library for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pmorissette/ffn) (👨‍💻 26 · 🔀 180 · 📦 120 · 📋 81 - 11% open · ⏱️ 24.04.2021):

	```
	git clone https://github.com/pmorissette/ffn
	```
- [PyPi](https://pypi.org/project/ffn) (📥 15K / month):
	```
	pip install ffn
	```
</details>
<details><summary><b><a href="https://github.com/quantopian/empyrical">empyrical</a></b> (🥈25 ·  ⭐ 770) - Common financial risk and performance metrics. Used by zipline and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/quantopian/empyrical) (👨‍💻 22 · 🔀 240 · 📦 590 · 📋 49 - 46% open · ⏱️ 14.10.2020):

	```
	git clone https://github.com/quantopian/empyrical
	```
- [PyPi](https://pypi.org/project/empyrical) (📥 65K / month):
	```
	pip install empyrical
	```
- [Conda](https://anaconda.org/conda-forge/empyrical) (📥 11K · ⏱️ 14.10.2020):
	```
	conda install -c conda-forge empyrical
	```
</details>
<details><summary><b><a href="https://github.com/quantopian/alphalens">Alphalens</a></b> (🥈24 ·  ⭐ 1.9K · 💤) - Performance analysis of predictive (alpha) stock factors. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/quantopian/alphalens) (👨‍💻 25 · 🔀 700 · 📦 380 · 📋 180 - 19% open · ⏱️ 27.04.2020):

	```
	git clone https://github.com/quantopian/alphalens
	```
- [PyPi](https://pypi.org/project/alphalens) (📥 3K / month):
	```
	pip install alphalens
	```
- [Conda](https://anaconda.org/conda-forge/alphalens) (📥 11K · ⏱️ 16.05.2020):
	```
	conda install -c conda-forge alphalens
	```
</details>
<details><summary><b><a href="https://github.com/RomelTorres/alpha_vantage">Alpha Vantage</a></b> (🥉23 ·  ⭐ 3.3K) - A python wrapper for Alpha Vantage API for financial data. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/RomelTorres/alpha_vantage) (👨‍💻 36 · 🔀 590 · 📋 240 - 5% open · ⏱️ 21.12.2020):

	```
	git clone https://github.com/RomelTorres/alpha_vantage
	```
- [PyPi](https://pypi.org/project/alpha_vantage) (📥 31K / month):
	```
	pip install alpha_vantage
	```
</details>
<details><summary><b><a href="https://github.com/peerchemist/finta">FinTA</a></b> (🥉23 ·  ⭐ 1K) - Common financial technical indicators implemented in Pandas. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code></summary>

- [GitHub](https://github.com/peerchemist/finta) (👨‍💻 24 · 🔀 320 · 📦 70 · 📋 70 - 11% open · ⏱️ 17.04.2021):

	```
	git clone https://github.com/peerchemist/finta
	```
- [PyPi](https://pypi.org/project/finta) (📥 8.2K / month):
	```
	pip install finta
	```
</details>
<details><summary><b><a href="https://github.com/bashtage/arch">arch</a></b> (🥉23 ·  ⭐ 700) - ARCH models in Python. <code><a href="https://tldrlegal.com/search?q=NCSA">❗️NCSA</a></code></summary>

- [GitHub](https://github.com/bashtage/arch) (👨‍💻 26 · 🔀 160 · 📦 280 · 📋 150 - 6% open · ⏱️ 22.04.2021):

	```
	git clone https://github.com/bashtage/arch
	```
- [PyPi](https://pypi.org/project/arch) (📥 71K / month):
	```
	pip install arch
	```
</details>
<details><summary><b><a href="https://github.com/gbeced/pyalgotrade">PyAlgoTrade</a></b> (🥉22 ·  ⭐ 3.3K · 💀) - Python Algorithmic Trading Library. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/gbeced/pyalgotrade) (👨‍💻 11 · 🔀 1.1K · 📦 73 · 📋 120 - 29% open · ⏱️ 21.08.2018):

	```
	git clone https://github.com/gbeced/pyalgotrade
	```
- [PyPi](https://pypi.org/project/pyalgotrade) (📥 790 / month):
	```
	pip install pyalgotrade
	```
</details>
<details><summary><b><a href="https://github.com/tensortrade-org/tensortrade">TensorTrade</a></b> (🥉22 ·  ⭐ 3.2K) - An open source reinforcement learning framework for training,.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/tensortrade-org/tensortrade) (👨‍💻 50 · 🔀 690 · 📦 15 · 📋 170 - 13% open · ⏱️ 24.03.2021):

	```
	git clone https://github.com/tensortrade-org/tensortrade
	```
- [PyPi](https://pypi.org/project/tensortrade) (📥 1.6K / month):
	```
	pip install tensortrade
	```
</details>
<details><summary><b><a href="https://github.com/cuemacro/finmarketpy">finmarketpy</a></b> (🥉21 ·  ⭐ 2.6K) - Python library for backtesting trading strategies & analyzing.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/cuemacro/finmarketpy) (👨‍💻 14 · 🔀 400 · 📥 39 · 📦 3 · 📋 25 - 88% open · ⏱️ 21.04.2021):

	```
	git clone https://github.com/cuemacro/finmarketpy
	```
- [PyPi](https://pypi.org/project/finmarketpy) (📥 150 / month):
	```
	pip install finmarketpy
	```
</details>
<details><summary><b><a href="https://github.com/enigmampc/catalyst">Enigma Catalyst</a></b> (🥉21 ·  ⭐ 2.1K) - An Algorithmic Trading Library for Crypto-Assets in Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/enigmampc/catalyst) (👨‍💻 140 · 🔀 610 · 📦 22 · 📋 490 - 25% open · ⏱️ 28.12.2020):

	```
	git clone https://github.com/enigmampc/catalyst
	```
- [PyPi](https://pypi.org/project/enigma-catalyst) (📥 2.7K / month):
	```
	pip install enigma-catalyst
	```
</details>
<details><summary><b><a href="https://github.com/erdewit/ib_insync">IB-insync</a></b> (🥉21 ·  ⭐ 1.4K) - Python sync/async framework for Interactive Brokers API. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/erdewit/ib_insync) (👨‍💻 28 · 🔀 410 · 📋 300 - 0% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/erdewit/ib_insync
	```
- [PyPi](https://pypi.org/project/ib_insync) (📥 7.8K / month):
	```
	pip install ib_insync
	```
- [Conda](https://anaconda.org/conda-forge/ib-insync) (📥 9.3K · ⏱️ 25.02.2021):
	```
	conda install -c conda-forge ib-insync
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/qlib">Qlib</a></b> (🥉20 ·  ⭐ 4.9K) - Qlib is an AI-oriented quantitative investment platform, which aims to.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/microsoft/qlib) (👨‍💻 39 · 🔀 780 · 📥 230 · 📦 2 · 📋 210 - 53% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/microsoft/qlib
	```
- [PyPi](https://pypi.org/project/pyqlib) (📥 4.8K / month):
	```
	pip install pyqlib
	```
</details>
<details><summary><b><a href="https://github.com/google/tf-quant-finance">tf-quant-finance</a></b> (🥉20 ·  ⭐ 2.6K) - High-performance TensorFlow library for quantitative.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/google/tf-quant-finance) (👨‍💻 30 · 🔀 320 · 📦 4 · 📋 23 - 52% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/google/tf-quant-finance
	```
- [PyPi](https://pypi.org/project/tf-quant-finance) (📥 360 / month):
	```
	pip install tf-quant-finance
	```
</details>
<details><summary><b><a href="https://github.com/jealous/stockstats">stockstats</a></b> (🥉20 ·  ⭐ 760) - Supply a wrapper ``StockDataFrame`` based on the.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jealous/stockstats) (👨‍💻 7 · 🔀 210 · 📦 230 · 📋 58 - 46% open · ⏱️ 17.10.2020):

	```
	git clone https://github.com/jealous/stockstats
	```
- [PyPi](https://pypi.org/project/stockstats) (📥 43K / month):
	```
	pip install stockstats
	```
</details>
<details><summary><b><a href="https://github.com/CryptoSignal/Crypto-Signal">Crypto Signals</a></b> (🥉18 ·  ⭐ 3K · 💤) - Github.com/CryptoSignal - #1 Quant Trading & Technical.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/CryptoSignal/Crypto-Signal) (👨‍💻 25 · 🔀 760 · 📋 230 - 16% open · ⏱️ 03.09.2020):

	```
	git clone https://github.com/CryptoSignal/crypto-signal
	```
- [Docker Hub](https://hub.docker.com/r/shadowreaver/crypto-signal) (📥 44K · ⭐ 8 · ⏱️ 03.09.2020):
	```
	docker pull shadowreaver/crypto-signal
	```
</details>
<details><summary><b><a href="https://github.com/kernc/backtesting.py">Backtesting.py</a></b> (🥉17 ·  ⭐ 1.3K) - Backtest trading strategies in Python. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/kernc/backtesting.py) (👨‍💻 12 · 🔀 290 · 📋 210 - 11% open · ⏱️ 22.04.2021):

	```
	git clone https://github.com/kernc/backtesting.py
	```
- [PyPi](https://pypi.org/project/backtesting) (📥 5.6K / month):
	```
	pip install backtesting
	```
</details>
<details><summary><b><a href="https://github.com/tradytics/surpriver">surpriver</a></b> (🥉12 ·  ⭐ 1.2K · 💤) - Find big moving stocks before they move using machine.. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/tradytics/surpriver) (👨‍💻 6 · 🔀 220 · 📋 13 - 61% open · ⏱️ 21.09.2020):

	```
	git clone https://github.com/tradytics/surpriver
	```
</details>
<br>

## Time Series Data

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for forecasting, anomaly detection, feature extraction, and machine learning on time-series and sequential data._

<details><summary><b><a href="https://github.com/alkaline-ml/pmdarima">pmdarima</a></b> (🥇27 ·  ⭐ 870) - A statistical library designed to fill the void in Python's time series.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/alkaline-ml/pmdarima) (👨‍💻 17 · 🔀 160 · 📦 900 · 📋 230 - 7% open · ⏱️ 19.04.2021):

	```
	git clone https://github.com/alkaline-ml/pmdarima
	```
- [PyPi](https://pypi.org/project/pmdarima) (📥 380K / month):
	```
	pip install pmdarima
	```
</details>
<details><summary><b><a href="https://github.com/facebook/prophet">Prophet</a></b> (🥇26 ·  ⭐ 13K) - Tool for producing high quality forecasts for time series data that has.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebook/prophet) (👨‍💻 130 · 🔀 3.6K · 📥 590 · 📋 1.6K - 3% open · ⏱️ 21.04.2021):

	```
	git clone https://github.com/facebook/prophet
	```
- [PyPi](https://pypi.org/project/fbprophet) (📥 740K / month):
	```
	pip install fbprophet
	```
</details>
<details><summary><b><a href="https://github.com/tslearn-team/tslearn">tslearn</a></b> (🥈25 ·  ⭐ 1.6K) - A machine learning toolkit dedicated to time-series data. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tslearn-team/tslearn) (👨‍💻 30 · 🔀 230 · 📦 220 · 📋 230 - 27% open · ⏱️ 25.01.2021):

	```
	git clone https://github.com/tslearn-team/tslearn
	```
- [PyPi](https://pypi.org/project/tslearn) (📥 64K / month):
	```
	pip install tslearn
	```
- [Conda](https://anaconda.org/conda-forge/tslearn) (📥 210K · ⏱️ 25.01.2021):
	```
	conda install -c conda-forge tslearn
	```
</details>
<details><summary><b><a href="https://github.com/blue-yonder/tsfresh">tsfresh</a></b> (🥈24 ·  ⭐ 5.6K) - Automatic extraction of relevant features from time series:. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/blue-yonder/tsfresh) (👨‍💻 76 · 🔀 860 · 📋 460 - 7% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/blue-yonder/tsfresh
	```
- [PyPi](https://pypi.org/project/tsfresh) (📥 240K / month):
	```
	pip install tsfresh
	```
- [Conda](https://anaconda.org/conda-forge/tsfresh) (📥 33K · ⏱️ 07.03.2021):
	```
	conda install -c conda-forge tsfresh
	```
</details>
<details><summary><b><a href="https://github.com/alan-turing-institute/sktime">sktime</a></b> (🥈24 ·  ⭐ 3.9K) - A unified framework for machine learning with time series. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/alan-turing-institute/sktime) (👨‍💻 83 · 🔀 520 · 📥 57 · 📦 140 · 📋 390 - 22% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/alan-turing-institute/sktime
	```
- [PyPi](https://pypi.org/project/sktime) (📥 53K / month):
	```
	pip install sktime
	```
</details>
<details><summary><b><a href="https://github.com/awslabs/gluon-ts">GluonTS</a></b> (🥈23 ·  ⭐ 1.9K) - Probabilistic time series modeling in Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/awslabs/gluon-ts) (👨‍💻 71 · 🔀 390 · 📋 540 - 31% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/awslabs/gluon-ts
	```
- [PyPi](https://pypi.org/project/gluonts) (📥 33K / month):
	```
	pip install gluonts
	```
</details>
<details><summary><b><a href="https://github.com/TDAmeritrade/stumpy">STUMPY</a></b> (🥈22 ·  ⭐ 1.8K) - STUMPY is a powerful and scalable Python library for computing a Matrix.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/TDAmeritrade/stumpy) (👨‍💻 21 · 🔀 170 · 📋 230 - 10% open · ⏱️ 20.04.2021):

	```
	git clone https://github.com/TDAmeritrade/stumpy
	```
- [PyPi](https://pypi.org/project/stumpy) (📥 66K / month):
	```
	pip install stumpy
	```
- [Conda](https://anaconda.org/conda-forge/stumpy) (📥 20K · ⏱️ 05.02.2021):
	```
	conda install -c conda-forge stumpy
	```
</details>
<details><summary><b><a href="https://github.com/python-streamz/streamz">Streamz</a></b> (🥈21 ·  ⭐ 940) - Real-time stream processing for python. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/python-streamz/streamz) (👨‍💻 39 · 🔀 120 · 📦 200 · 📋 220 - 40% open · ⏱️ 05.04.2021):

	```
	git clone https://github.com/python-streamz/streamz
	```
- [PyPi](https://pypi.org/project/streamz) (📥 8K / month):
	```
	pip install streamz
	```
- [Conda](https://anaconda.org/conda-forge/streamz) (📥 150K · ⏱️ 15.01.2021):
	```
	conda install -c conda-forge streamz
	```
</details>
<details><summary><b><a href="https://github.com/RJT1990/pyflux">PyFlux</a></b> (🥉20 ·  ⭐ 1.9K · 💀) - Open source time series library for Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/RJT1990/pyflux) (👨‍💻 6 · 🔀 210 · 📦 180 · 📋 140 - 54% open · ⏱️ 16.12.2018):

	```
	git clone https://github.com/RJT1990/pyflux
	```
- [PyPi](https://pypi.org/project/pyflux) (📥 20K / month):
	```
	pip install pyflux
	```
</details>
<details><summary><b><a href="https://github.com/jdb78/pytorch-forecasting">pytorch-forecasting</a></b> (🥉20 ·  ⭐ 950) - Time series forecasting with PyTorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jdb78/pytorch-forecasting) (👨‍💻 16 · 🔀 110 · 📋 190 - 20% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/jdb78/pytorch-forecasting
	```
- [PyPi](https://pypi.org/project/pytorch-forecasting) (📥 11K / month):
	```
	pip install pytorch-forecasting
	```
</details>
<details><summary><b><a href="https://github.com/johannfaouzi/pyts">pyts</a></b> (🥉20 ·  ⭐ 930) - A Python package for time series classification. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/johannfaouzi/pyts) (👨‍💻 9 · 🔀 100 · 📦 100 · 📋 45 - 57% open · ⏱️ 31.03.2021):

	```
	git clone https://github.com/johannfaouzi/pyts
	```
- [PyPi](https://pypi.org/project/pyts) (📥 20K / month):
	```
	pip install pyts
	```
- [Conda](https://anaconda.org/conda-forge/pyts) (📥 7.2K · ⏱️ 21.03.2020):
	```
	conda install -c conda-forge pyts
	```
</details>
<details><summary><b><a href="https://github.com/unit8co/darts">Darts</a></b> (🥉20 ·  ⭐ 830) - A python library for easy manipulation and forecasting of time series. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/unit8co/darts) (👨‍💻 25 · 🔀 110 · 📦 2 · 📋 82 - 20% open · ⏱️ 19.04.2021):

	```
	git clone https://github.com/unit8co/darts
	```
- [PyPi](https://pypi.org/project/u8darts) (📥 2.6K / month):
	```
	pip install u8darts
	```
- [Docker Hub](https://hub.docker.com/r/unit8/darts) (📥 110 · ⏱️ 14.04.2021):
	```
	docker pull unit8/darts
	```
</details>
<details><summary><b><a href="https://github.com/wwrechard/pydlm">pydlm</a></b> (🥉19 ·  ⭐ 380 · 💀) - A python library for Bayesian time series modeling. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/wwrechard/pydlm) (👨‍💻 6 · 🔀 86 · 📦 18 · 📋 41 - 80% open · ⏱️ 22.10.2019):

	```
	git clone https://github.com/wwrechard/pydlm
	```
- [PyPi](https://pypi.org/project/pydlm) (📥 26K / month):
	```
	pip install pydlm
	```
</details>
<details><summary><b><a href="https://github.com/linkedin/luminol">luminol</a></b> (🥉18 ·  ⭐ 910 · 💀) - Anomaly Detection and Correlation library. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/linkedin/luminol) (👨‍💻 8 · 🔀 180 · 📦 38 · 📋 36 - 66% open · ⏱️ 09.01.2018):

	```
	git clone https://github.com/linkedin/luminol
	```
- [PyPi](https://pypi.org/project/luminol) (📥 43K / month):
	```
	pip install luminol
	```
</details>
<details><summary><b><a href="https://github.com/X-DataInitiative/tick">tick</a></b> (🥉18 ·  ⭐ 330 · 💤) - Module for statistical learning, with a particular emphasis on time-.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/X-DataInitiative/tick) (👨‍💻 16 · 🔀 74 · 📥 160 · 📦 30 · 📋 210 - 23% open · ⏱️ 15.06.2020):

	```
	git clone https://github.com/X-DataInitiative/tick
	```
- [PyPi](https://pypi.org/project/tick) (📥 1.3K / month):
	```
	pip install tick
	```
</details>
<details><summary><b><a href="https://github.com/arundo/adtk">ADTK</a></b> (🥉17 ·  ⭐ 650 · 💤) - A Python toolkit for rule-based/unsupervised anomaly detection in time.. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code></summary>

- [GitHub](https://github.com/arundo/adtk) (👨‍💻 11 · 🔀 83 · 📋 55 - 43% open · ⏱️ 17.04.2020):

	```
	git clone https://github.com/arundo/adtk
	```
- [PyPi](https://pypi.org/project/adtk) (📥 52K / month):
	```
	pip install adtk
	```
</details>
<details><summary><b><a href="https://github.com/target/matrixprofile-ts">matrixprofile-ts</a></b> (🥉17 ·  ⭐ 630 · 💤) - A Python library for detecting patterns and anomalies.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/target/matrixprofile-ts) (👨‍💻 15 · 🔀 92 · 📦 16 · 📋 53 - 35% open · ⏱️ 25.04.2020):

	```
	git clone https://github.com/target/matrixprofile-ts
	```
- [PyPi](https://pypi.org/project/matrixprofile-ts) (📥 3.7K / month):
	```
	pip install matrixprofile-ts
	```
</details>
<details><summary><b><a href="https://github.com/dmbee/seglearn">seglearn</a></b> (🥉17 ·  ⭐ 440) - Python module for machine learning time series:. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/dmbee/seglearn) (👨‍💻 13 · 🔀 47 · 📦 7 · 📋 27 - 18% open · ⏱️ 12.03.2021):

	```
	git clone https://github.com/dmbee/seglearn
	```
- [PyPi](https://pypi.org/project/seglearn) (📥 2.6K / month):
	```
	pip install seglearn
	```
</details>
<details><summary><b><a href="https://github.com/AutoViML/Auto_TS">Auto TS</a></b> (🥉17 ·  ⭐ 220) - Automatically build ARIMA, SARIMAX, VAR, FB Prophet and XGBoost.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/AutoViML/Auto_TS) (👨‍💻 6 · 🔀 41 · 📋 35 - 11% open · ⏱️ 14.03.2021):

	```
	git clone https://github.com/AutoViML/Auto_TS
	```
- [PyPi](https://pypi.org/project/auto-ts) (📥 1.2K / month):
	```
	pip install auto-ts
	```
</details>
<details><summary><b><a href="https://github.com/firmai/atspy">atspy</a></b> (🥉13 ·  ⭐ 350) - AtsPy: Automated Time Series Models in Python (by @firmai). <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/firmai/atspy) (👨‍💻 5 · 🔀 67 · 📦 3 · 📋 20 - 90% open · ⏱️ 12.11.2020):

	```
	git clone https://github.com/firmai/atspy
	```
- [PyPi](https://pypi.org/project/atspy) (📥 890 / month):
	```
	pip install atspy
	```
</details>
<br>

## Medical Data

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for processing and analyzing medical data such as MRIs, EEGs, genomic data, and other medical imaging formats._

<details><summary><b><a href="https://github.com/CamDavidsonPilon/lifelines">Lifelines</a></b> (🥇29 ·  ⭐ 1.6K) - Survival analysis in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/CamDavidsonPilon/lifelines) (👨‍💻 93 · 🔀 410 · 📦 550 · 📋 800 - 24% open · ⏱️ 15.04.2021):

	```
	git clone https://github.com/CamDavidsonPilon/lifelines
	```
- [PyPi](https://pypi.org/project/lifelines) (📥 250K / month):
	```
	pip install lifelines
	```
- [Conda](https://anaconda.org/conda-forge/lifelines) (📥 140K · ⏱️ 06.04.2021):
	```
	conda install -c conda-forge lifelines
	```
</details>
<details><summary><b><a href="https://github.com/nipy/nipype">NIPYPE</a></b> (🥇28 ·  ⭐ 560) - Workflows and interfaces for neuroimaging packages. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/nipy/nipype) (👨‍💻 210 · 🔀 430 · 📦 580 · 📋 1.2K - 26% open · ⏱️ 22.04.2021):

	```
	git clone https://github.com/nipy/nipype
	```
- [PyPi](https://pypi.org/project/nipype) (📥 19K / month):
	```
	pip install nipype
	```
- [Conda](https://anaconda.org/conda-forge/nipype) (📥 390K · ⏱️ 28.11.2020):
	```
	conda install -c conda-forge nipype
	```
</details>
<details><summary><b><a href="https://github.com/nipy/nibabel">NiBabel</a></b> (🥇28 ·  ⭐ 400) - Python package to access a cacophony of neuro-imaging file formats. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/nipy/nibabel) (👨‍💻 90 · 🔀 210 · 📦 4.2K · 📋 380 - 23% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/nipy/nibabel
	```
- [PyPi](https://pypi.org/project/nibabel) (📥 110K / month):
	```
	pip install nibabel
	```
- [Conda](https://anaconda.org/conda-forge/nibabel) (📥 330K · ⏱️ 29.11.2020):
	```
	conda install -c conda-forge nibabel
	```
</details>
<details><summary><b><a href="https://github.com/mne-tools/mne-python">MNE</a></b> (🥈27 ·  ⭐ 1.6K) - MNE: Magnetoencephalography (MEG) and Electroencephalography (EEG) in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/mne-tools/mne-python) (👨‍💻 260 · 🔀 880 · 📦 930 · 📋 3.6K - 8% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/mne-tools/mne-python
	```
- [PyPi](https://pypi.org/project/mne) (📥 41K / month):
	```
	pip install mne
	```
- [Conda](https://anaconda.org/conda-forge/mne) (📥 130K · ⏱️ 27.04.2021):
	```
	conda install -c conda-forge mne
	```
</details>
<details><summary><b><a href="https://github.com/nilearn/nilearn">Nilearn</a></b> (🥈26 ·  ⭐ 730) - Machine learning for NeuroImaging in Python. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/nilearn/nilearn) (👨‍💻 170 · 🔀 390 · 📦 980 · 📋 1.4K - 15% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/nilearn/nilearn
	```
- [PyPi](https://pypi.org/project/nilearn) (📥 24K / month):
	```
	pip install nilearn
	```
- [Conda](https://anaconda.org/conda-forge/nilearn) (📥 94K · ⏱️ 10.03.2021):
	```
	conda install -c conda-forge nilearn
	```
</details>
<details><summary><b><a href="https://github.com/hail-is/hail">Hail</a></b> (🥈24 ·  ⭐ 720) - Scalable genomic data analysis. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/hail-is/hail) (👨‍💻 73 · 🔀 180 · 📦 37 · 📋 2K - 0% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/hail-is/hail
	```
- [PyPi](https://pypi.org/project/hail) (📥 5.2K / month):
	```
	pip install hail
	```
</details>
<details><summary><b><a href="https://github.com/dipy/dipy">DIPY</a></b> (🥈24 ·  ⭐ 430) - DIPY is the paragon 3D/4D+ imaging library in Python. Contains.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/dipy/dipy) (👨‍💻 120 · 🔀 300 · 📦 360 · 📋 690 - 12% open · ⏱️ 25.04.2021):

	```
	git clone https://github.com/dipy/dipy
	```
- [PyPi](https://pypi.org/project/dipy) (📥 12K / month):
	```
	pip install dipy
	```
- [Conda](https://anaconda.org/conda-forge/dipy) (📥 210K · ⏱️ 14.03.2021):
	```
	conda install -c conda-forge dipy
	```
</details>
<details><summary><b><a href="https://github.com/Project-MONAI/MONAI">MONAI</a></b> (🥈22 ·  ⭐ 1.9K) - AI Toolkit for Healthcare Imaging. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/Project-MONAI/MONAI) (👨‍💻 57 · 🔀 350 · 📋 850 - 10% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/Project-MONAI/MONAI
	```
- [PyPi](https://pypi.org/project/monai) (📥 7.3K / month):
	```
	pip install monai
	```
</details>
<details><summary><b><a href="https://github.com/google/deepvariant">DeepVariant</a></b> (🥉21 ·  ⭐ 2.3K) - DeepVariant is an analysis pipeline that uses a deep neural.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/google/deepvariant) (👨‍💻 19 · 🔀 540 · 📥 3.3K · 📋 400 - 0% open · ⏱️ 31.03.2021):

	```
	git clone https://github.com/google/deepvariant
	```
- [Conda](https://anaconda.org/bioconda/deepvariant) (📥 29K · ⏱️ 18.04.2021):
	```
	conda install -c bioconda deepvariant
	```
</details>
<details><summary><b><a href="https://github.com/NifTK/NiftyNet">NiftyNet</a></b> (🥉20 ·  ⭐ 1.3K · 💤) - [unmaintained] An open-source convolutional neural.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/NifTK/NiftyNet) (👨‍💻 58 · 🔀 380 · 📋 320 - 30% open · ⏱️ 21.04.2020):

	```
	git clone https://github.com/NifTK/NiftyNet
	```
- [PyPi](https://pypi.org/project/niftynet) (📥 270 / month):
	```
	pip install niftynet
	```
</details>
<details><summary><b><a href="https://github.com/loli/medpy">MedPy</a></b> (🥉20 ·  ⭐ 340 · 💤) - Medical image processing in Python. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/loli/medpy) (👨‍💻 13 · 🔀 110 · 📦 260 · 📋 76 - 13% open · ⏱️ 01.05.2020):

	```
	git clone https://github.com/loli/medpy
	```
- [PyPi](https://pypi.org/project/MedPy) (📥 7.9K / month):
	```
	pip install MedPy
	```
</details>
<details><summary><b><a href="https://github.com/projectglow/glow">Glow</a></b> (🥉20 ·  ⭐ 170) - An open-source toolkit for large-scale genomic analysis. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/projectglow/glow) (👨‍💻 12 · 🔀 44 · 📋 83 - 30% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/projectglow/glow
	```
- [PyPi](https://pypi.org/project/glow.py) (📥 14K / month):
	```
	pip install glow.py
	```
</details>
<details><summary><b><a href="https://github.com/nipy/nipy">NIPY</a></b> (🥉19 ·  ⭐ 300) - Neuroimaging in Python FMRI analysis package. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/nipy/nipy) (👨‍💻 63 · 🔀 120 · 📋 150 - 25% open · ⏱️ 29.03.2021):

	```
	git clone https://github.com/nipy/nipy
	```
- [PyPi](https://pypi.org/project/nipy) (📥 2.2K / month):
	```
	pip install nipy
	```
- [Conda](https://anaconda.org/conda-forge/nipy) (📥 78K · ⏱️ 04.05.2020):
	```
	conda install -c conda-forge nipy
	```
</details>
<details><summary><b><a href="https://github.com/DLTK/DLTK">DLTK</a></b> (🥉18 ·  ⭐ 1.3K · 💀) - Deep Learning Toolkit for Medical Image Analysis. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/DLTK/DLTK) (👨‍💻 9 · 🔀 390 · 📦 20 · 📋 31 - 22% open · ⏱️ 21.01.2019):

	```
	git clone https://github.com/DLTK/DLTK
	```
- [PyPi](https://pypi.org/project/dltk) (📥 180 / month):
	```
	pip install dltk
	```
</details>
<details><summary><b><a href="https://github.com/brainiak/brainiak">Brainiak</a></b> (🥉18 ·  ⭐ 240) - Brain Imaging Analysis Kit. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/brainiak/brainiak) (👨‍💻 32 · 🔀 110 · 📦 12 · 📋 190 - 35% open · ⏱️ 19.02.2021):

	```
	git clone https://github.com/brainiak/brainiak
	```
- [PyPi](https://pypi.org/project/brainiak) (📥 380 / month):
	```
	pip install brainiak
	```
- [Docker Hub](https://hub.docker.com/r/brainiak/brainiak) (📥 530 · ⭐ 1 · ⏱️ 15.10.2020):
	```
	docker pull brainiak/brainiak
	```
</details>
<details><summary><b><a href="https://github.com/perone/medicaltorch">MedicalTorch</a></b> (🥉16 ·  ⭐ 730) - A medical imaging framework for Pytorch. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/perone/medicaltorch) (👨‍💻 8 · 🔀 110 · 📦 10 · 📋 22 - 59% open · ⏱️ 16.04.2021):

	```
	git clone https://github.com/perone/medicaltorch
	```
- [PyPi](https://pypi.org/project/medicaltorch) (📥 230 / month):
	```
	pip install medicaltorch
	```
</details>
<details><summary><b><a href="https://github.com/Tencent/MedicalNet">MedicalNet</a></b> (🥉13 ·  ⭐ 1.1K · 💤) - Many studies have shown that the performance on deep learning is.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Tencent/MedicalNet) (🔀 300 · 📋 59 - 76% open · ⏱️ 27.08.2020):

	```
	git clone https://github.com/Tencent/MedicalNet
	```
</details>
<details><summary><b><a href="https://github.com/MIC-DKFZ/medicaldetectiontoolkit">Medical Detection Toolkit</a></b> (🥉13 ·  ⭐ 940) - The Medical Detection Toolkit contains 2D + 3D.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/MIC-DKFZ/medicaldetectiontoolkit) (👨‍💻 3 · 🔀 240 · 📋 110 - 24% open · ⏱️ 30.03.2021):

	```
	git clone https://github.com/MIC-DKFZ/medicaldetectiontoolkit
	```
</details>
<details><summary><b><a href="https://github.com/QTIM-Lab/DeepNeuro">DeepNeuro</a></b> (🥉12 ·  ⭐ 100 · 💤) - A deep learning python package for neuroimaging data. Made by:. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/QTIM-Lab/DeepNeuro) (👨‍💻 6 · 🔀 32 · 📦 1 · 📋 41 - 60% open · ⏱️ 24.06.2020):

	```
	git clone https://github.com/QTIM-Lab/DeepNeuro
	```
- [PyPi](https://pypi.org/project/deepneuro) (📥 88 / month):
	```
	pip install deepneuro
	```
</details>
<br>

## Optical Character Recognition

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for optical character recognition (OCR) and text extraction from images or videos._

<details><summary><b><a href="https://github.com/JaidedAI/EasyOCR">EasyOCR</a></b> (🥇29 ·  ⭐ 11K) - Ready-to-use OCR with 80+ supported languages and all popular writing.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/JaidedAI/EasyOCR) (👨‍💻 77 · 🔀 1.2K · 📥 260K · 📦 200 · 📋 300 - 39% open · ⏱️ 21.04.2021):

	```
	git clone https://github.com/JaidedAI/EasyOCR
	```
- [PyPi](https://pypi.org/project/easyocr) (📥 17K / month):
	```
	pip install easyocr
	```
</details>
<details><summary><b><a href="https://github.com/sirfz/tesserocr">tesserocr</a></b> (🥇27 ·  ⭐ 1.4K) - A Python wrapper for the tesseract-ocr API. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/sirfz/tesserocr) (👨‍💻 24 · 🔀 190 · 📦 490 · 📋 210 - 28% open · ⏱️ 23.03.2021):

	```
	git clone https://github.com/sirfz/tesserocr
	```
- [PyPi](https://pypi.org/project/tesserocr) (📥 75K / month):
	```
	pip install tesserocr
	```
- [Conda](https://anaconda.org/conda-forge/tesserocr) (📥 43K · ⏱️ 13.01.2021):
	```
	conda install -c conda-forge tesserocr
	```
</details>
<details><summary><b><a href="https://github.com/PaddlePaddle/PaddleOCR">PaddleOCR</a></b> (🥈25 ·  ⭐ 12K) - Awesome multilingual OCR toolkits based on PaddlePaddle.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PaddlePaddle/PaddleOCR) (👨‍💻 42 · 🔀 2.4K · 📦 92 · 📋 1.8K - 37% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/PaddlePaddle/PaddleOCR
	```
- [PyPi](https://pypi.org/project/paddleocr) (📥 4.7K / month):
	```
	pip install paddleocr
	```
</details>
<details><summary><b><a href="https://github.com/jbarlow83/OCRmyPDF">OCRmyPDF</a></b> (🥈25 ·  ⭐ 4.2K) - OCRmyPDF adds an OCR text layer to scanned PDF files, allowing them.. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code></summary>

- [GitHub](https://github.com/jbarlow83/OCRmyPDF) (👨‍💻 53 · 🔀 440 · 📦 140 · 📋 690 - 12% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/jbarlow83/OCRmyPDF
	```
- [PyPi](https://pypi.org/project/ocrmypdf) (📥 19K / month):
	```
	pip install ocrmypdf
	```
</details>
<details><summary><b><a href="https://github.com/madmaze/pytesseract">Tesseract</a></b> (🥈25 ·  ⭐ 3.6K) - Python-tesseract is an optical character recognition (OCR) tool.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/madmaze/pytesseract) (👨‍💻 37 · 🔀 510 · 📋 260 - 2% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/madmaze/pytesseract
	```
- [PyPi](https://pypi.org/project/pytesseract) (📥 790K / month):
	```
	pip install pytesseract
	```
- [Conda](https://anaconda.org/conda-forge/pytesseract) (📥 250K · ⏱️ 20.11.2020):
	```
	conda install -c conda-forge pytesseract
	```
</details>
<details><summary><b><a href="https://github.com/emedvedev/attention-ocr">attention-ocr</a></b> (🥉21 ·  ⭐ 860) - A Tensorflow model for text recognition (CNN + seq2seq with.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/emedvedev/attention-ocr) (👨‍💻 27 · 🔀 230 · 📦 16 · 📋 140 - 13% open · ⏱️ 31.10.2020):

	```
	git clone https://github.com/emedvedev/attention-ocr
	```
- [PyPi](https://pypi.org/project/aocr) (📥 400 / month):
	```
	pip install aocr
	```
</details>
<details><summary><b><a href="https://github.com/Calamari-OCR/calamari">calamari</a></b> (🥉20 ·  ⭐ 810) - Line based ATR Engine based on OCRopy. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Calamari-OCR/calamari) (👨‍💻 17 · 🔀 170 · 📋 180 - 16% open · ⏱️ 27.03.2021):

	```
	git clone https://github.com/Calamari-OCR/calamari
	```
- [PyPi](https://pypi.org/project/calamari_ocr) (📥 1.2K / month):
	```
	pip install calamari_ocr
	```
</details>
<details><summary><b><a href="https://github.com/faustomorales/keras-ocr">keras-ocr</a></b> (🥉19 ·  ⭐ 830) - A packaged and flexible version of the CRAFT text detector and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/faustomorales/keras-ocr) (👨‍💻 10 · 🔀 200 · 📥 39K · 📋 130 - 27% open · ⏱️ 31.03.2021):

	```
	git clone https://github.com/faustomorales/keras-ocr
	```
- [PyPi](https://pypi.org/project/keras-ocr) (📥 4.1K / month):
	```
	pip install keras-ocr
	```
</details>
<details><summary><b><a href="https://github.com/WZBSocialScienceCenter/pdftabextract">pdftabextract</a></b> (🥉17 ·  ⭐ 1.9K · 💀) - A set of tools for extracting tables from PDF files.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/WZBSocialScienceCenter/pdftabextract) (👨‍💻 2 · 🔀 330 · 📦 37 · 📋 21 - 14% open · ⏱️ 26.10.2018):

	```
	git clone https://github.com/WZBSocialScienceCenter/pdftabextract
	```
- [PyPi](https://pypi.org/project/pdftabextract) (📥 400 / month):
	```
	pip install pdftabextract
	```
</details>
<details><summary><b><a href="https://github.com/jlsutherland/doc2text">doc2text</a></b> (🥉16 ·  ⭐ 1.2K) - Detect text blocks and OCR poorly scanned PDFs in bulk. Python module.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jlsutherland/doc2text) (👨‍💻 5 · 🔀 93 · 📦 35 · 📋 20 - 55% open · ⏱️ 01.12.2020):

	```
	git clone https://github.com/jlsutherland/doc2text
	```
- [PyPi](https://pypi.org/project/doc2text) (📥 500 / month):
	```
	pip install doc2text
	```
</details>
<details><summary><b><a href="https://github.com/aashrafh/Mozart">Mozart</a></b> (🥉10 ·  ⭐ 250 · 🐣) - An optical music recognition (OMR) system. Converts sheet.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/aashrafh/Mozart) (👨‍💻 5 · 🔀 40 · 📋 3 - 33% open · ⏱️ 04.04.2021):

	```
	git clone https://github.com/aashrafh/Mozart
	```
</details>
<br>

## Data Containers & Structures

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_General-purpose data containers & structures as well as utilities & extensions for pandas._

<details><summary><b><a href="https://github.com/pandas-dev/pandas">pandas</a></b> (🥇43 ·  ⭐ 29K) - Flexible and powerful data analysis / manipulation library for.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pandas-dev/pandas) (👨‍💻 2.7K · 🔀 12K · 📥 100K · 📦 430K · 📋 20K - 17% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/pandas-dev/pandas
	```
- [PyPi](https://pypi.org/project/pandas) (📥 46M / month):
	```
	pip install pandas
	```
- [Conda](https://anaconda.org/conda-forge/pandas) (📥 16M · ⏱️ 13.04.2021):
	```
	conda install -c conda-forge pandas
	```
</details>
<details><summary><b><a href="https://github.com/numpy/numpy">numpy</a></b> (🥇38 ·  ⭐ 17K) - The fundamental package for scientific computing with Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/numpy/numpy) (👨‍💻 1.3K · 🔀 5.3K · 📥 330K · 📦 690K · 📋 9.5K - 21% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/numpy/numpy
	```
- [PyPi](https://pypi.org/project/numpy) (📥 71M / month):
	```
	pip install numpy
	```
- [Conda](https://anaconda.org/conda-forge/numpy) (📥 19M · ⏱️ 28.03.2021):
	```
	conda install -c conda-forge numpy
	```
</details>
<details><summary><b><a href="https://github.com/h5py/h5py">h5py</a></b> (🥇36 ·  ⭐ 1.5K) - HDF5 for Python -- The h5py package is a Pythonic interface to the HDF5.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/h5py/h5py) (👨‍💻 160 · 🔀 390 · 📥 1K · 📦 110K · 📋 1.2K - 16% open · ⏱️ 20.04.2021):

	```
	git clone https://github.com/h5py/h5py
	```
- [PyPi](https://pypi.org/project/h5py) (📥 9.1M / month):
	```
	pip install h5py
	```
- [Conda](https://anaconda.org/conda-forge/h5py) (📥 5.1M · ⏱️ 16.04.2021):
	```
	conda install -c conda-forge h5py
	```
</details>
<details><summary><b><a href="https://github.com/pydata/xarray">xarray</a></b> (🥈33 ·  ⭐ 2K) - N-D labeled arrays and datasets in Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/pydata/xarray) (👨‍💻 310 · 🔀 650 · 📦 5.9K · 📋 2.7K - 26% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/pydata/xarray
	```
- [PyPi](https://pypi.org/project/xarray) (📥 520K / month):
	```
	pip install xarray
	```
- [Conda](https://anaconda.org/conda-forge/xarray) (📥 2.7M · ⏱️ 26.02.2021):
	```
	conda install -c conda-forge xarray
	```
</details>
<details><summary><b><a href="https://github.com/apache/arrow">Arrow</a></b> (🥈30 ·  ⭐ 7.8K) - Apache Arrow is a cross-language development platform for in-.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/apache/arrow) (👨‍💻 670 · 🔀 1.8K · 📦 39 · 📋 590 - 0% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/apache/arrow
	```
- [PyPi](https://pypi.org/project/pyarrow) (📥 23M / month):
	```
	pip install pyarrow
	```
- [Conda](https://anaconda.org/conda-forge/arrow) (📥 550K · ⏱️ 28.04.2021):
	```
	conda install -c conda-forge arrow
	```
</details>
<details><summary><b><a href="https://github.com/databricks/koalas">Koalas</a></b> (🥈29 ·  ⭐ 2.8K) - Koalas: pandas API on Apache Spark. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/databricks/koalas) (👨‍💻 50 · 🔀 300 · 📥 1K · 📦 89 · 📋 530 - 17% open · ⏱️ 15.04.2021):

	```
	git clone https://github.com/databricks/koalas
	```
- [PyPi](https://pypi.org/project/koalas) (📥 2.9M / month):
	```
	pip install koalas
	```
- [Conda](https://anaconda.org/conda-forge/koalas) (📥 86K · ⏱️ 09.03.2021):
	```
	conda install -c conda-forge koalas
	```
</details>
<details><summary><b><a href="https://github.com/pydata/bottleneck">Bottleneck</a></b> (🥈28 ·  ⭐ 600) - Fast NumPy array functions written in C. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/pydata/bottleneck) (👨‍💻 21 · 🔀 65 · 📦 21K · 📋 210 - 14% open · ⏱️ 24.01.2021):

	```
	git clone https://github.com/pydata/bottleneck
	```
- [PyPi](https://pypi.org/project/Bottleneck) (📥 380K / month):
	```
	pip install Bottleneck
	```
- [Conda](https://anaconda.org/conda-forge/bottleneck) (📥 1.5M · ⏱️ 21.01.2021):
	```
	conda install -c conda-forge bottleneck
	```
</details>
<details><summary><b><a href="https://github.com/modin-project/modin">Modin</a></b> (🥈27 ·  ⭐ 6K) - Modin: Speed up your Pandas workflows by changing a single line.. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/modin-project/modin) (👨‍💻 74 · 🔀 420 · 📥 200K · 📦 350 · 📋 1.7K - 28% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/modin-project/modin
	```
- [PyPi](https://pypi.org/project/modin) (📥 140K / month):
	```
	pip install modin
	```
</details>
<details><summary><b><a href="https://github.com/scikit-learn-contrib/sklearn-pandas">sklearn-pandas</a></b> (🥈27 ·  ⭐ 2.4K) - Pandas integration with sklearn. <code><a href="https://tldrlegal.com/search?q=Zlib">❗️Zlib</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/scikit-learn-contrib/sklearn-pandas) (👨‍💻 37 · 🔀 360 · 📦 2.1K · 📋 140 - 16% open · ⏱️ 27.02.2021):

	```
	git clone https://github.com/scikit-learn-contrib/sklearn-pandas
	```
- [PyPi](https://pypi.org/project/sklearn-pandas) (📥 210K / month):
	```
	pip install sklearn-pandas
	```
</details>
<details><summary><b><a href="https://github.com/ekzhu/datasketch">datasketch</a></b> (🥈27 ·  ⭐ 1.5K) - MinHash, LSH, LSH Forest, Weighted MinHash, HyperLogLog,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ekzhu/datasketch) (👨‍💻 17 · 🔀 210 · 📥 16 · 📦 280 · 📋 110 - 17% open · ⏱️ 24.02.2021):

	```
	git clone https://github.com/ekzhu/datasketch
	```
- [PyPi](https://pypi.org/project/datasketch) (📥 240K / month):
	```
	pip install datasketch
	```
</details>
<details><summary><b><a href="https://github.com/blaze/blaze">Blaze</a></b> (🥈26 ·  ⭐ 2.9K · 💀) - NumPy and Pandas interface to Big Data. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/blaze/blaze) (👨‍💻 64 · 🔀 350 · 📦 7.6K · 📋 750 - 33% open · ⏱️ 15.08.2019):

	```
	git clone https://github.com/blaze/blaze
	```
- [PyPi](https://pypi.org/project/blaze) (📥 12K / month):
	```
	pip install blaze
	```
- [Conda](https://anaconda.org/conda-forge/blaze) (📥 190K · ⏱️ 15.07.2018):
	```
	conda install -c conda-forge blaze
	```
</details>
<details><summary><b><a href="https://github.com/zarr-developers/zarr-python">zarr</a></b> (🥈26 ·  ⭐ 690) - An implementation of chunked, compressed, N-dimensional arrays for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/zarr-developers/zarr-python) (👨‍💻 38 · 🔀 110 · 📦 650 · 📋 390 - 39% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/zarr-developers/zarr-python
	```
- [PyPi](https://pypi.org/project/zarr) (📥 95K / month):
	```
	pip install zarr
	```
- [Conda](https://anaconda.org/conda-forge/zarr) (📥 700K · ⏱️ 27.04.2021):
	```
	conda install -c conda-forge zarr
	```
</details>
<details><summary><b><a href="https://github.com/pydata/numexpr">numexpr</a></b> (🥉25 ·  ⭐ 1.6K) - Fast numerical array expression evaluator for Python, NumPy, PyTables,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pydata/numexpr) (👨‍💻 57 · 🔀 160 · 📋 300 - 17% open · ⏱️ 03.03.2021):

	```
	git clone https://github.com/pydata/numexpr
	```
- [PyPi](https://pypi.org/project/numexpr) (📥 1.2M / month):
	```
	pip install numexpr
	```
- [Conda](https://anaconda.org/conda-forge/numexpr) (📥 2.5M · ⏱️ 05.03.2021):
	```
	conda install -c conda-forge numexpr
	```
</details>
<details><summary><b><a href="https://github.com/nalepae/pandarallel">Pandaral·lel</a></b> (🥉25 ·  ⭐ 1.5K) - A simple and efficient tool to parallelize Pandas.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/nalepae/pandarallel) (👨‍💻 14 · 🔀 100 · 📦 190 · 📋 120 - 55% open · ⏱️ 04.02.2021):

	```
	git clone https://github.com/nalepae/pandarallel
	```
- [PyPi](https://pypi.org/project/pandarallel) (📥 360K / month):
	```
	pip install pandarallel
	```
</details>
<details><summary><b><a href="https://github.com/msiemens/tinydb">TinyDB</a></b> (🥉24 ·  ⭐ 4.2K) - TinyDB is a lightweight document oriented database optimized for your.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/msiemens/tinydb) (👨‍💻 64 · 🔀 370 · 📋 250 - 2% open · ⏱️ 19.04.2021):

	```
	git clone https://github.com/msiemens/tinydb
	```
- [PyPi](https://pypi.org/project/tinydb) (📥 280K / month):
	```
	pip install tinydb
	```
- [Conda](https://anaconda.org/conda-forge/tinydb) (📥 110K · ⏱️ 11.02.2021):
	```
	conda install -c conda-forge tinydb
	```
</details>
<details><summary><b><a href="https://github.com/man-group/arctic">Arctic</a></b> (🥉24 ·  ⭐ 2.3K) - Arctic is a high performance datastore for numeric data. <code><a href="https://tldrlegal.com/search?q=LGPL-2.1">❗️LGPL-2.1</a></code></summary>

- [GitHub](https://github.com/man-group/arctic) (👨‍💻 71 · 🔀 440 · 📥 120 · 📦 110 · 📋 510 - 14% open · ⏱️ 16.04.2021):

	```
	git clone https://github.com/man-group/arctic
	```
- [PyPi](https://pypi.org/project/arctic) (📥 5.6K / month):
	```
	pip install arctic
	```
- [Conda](https://anaconda.org/conda-forge/arctic) (📥 13K · ⏱️ 16.12.2019):
	```
	conda install -c conda-forge arctic
	```
</details>
<details><summary><b><a href="https://github.com/jmcarpenter2/swifter">swifter</a></b> (🥉24 ·  ⭐ 1.6K) - A package which efficiently applies any function to a pandas.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/jmcarpenter2/swifter) (👨‍💻 14 · 🔀 76 · 📦 320 · 📋 95 - 20% open · ⏱️ 19.12.2020):

	```
	git clone https://github.com/jmcarpenter2/swifter
	```
- [PyPi](https://pypi.org/project/swifter) (📥 110K / month):
	```
	pip install swifter
	```
- [Conda](https://anaconda.org/conda-forge/swifter) (📥 94K · ⏱️ 05.04.2021):
	```
	conda install -c conda-forge swifter
	```
</details>
<details><summary><b><a href="https://github.com/PyTables/PyTables">PyTables</a></b> (🥉24 ·  ⭐ 1K) - A Python package to manage extremely large amounts of data. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/PyTables/PyTables) (👨‍💻 98 · 🔀 180 · 📥 130 · 📋 610 - 26% open · ⏱️ 20.03.2021):

	```
	git clone https://github.com/PyTables/PyTables
	```
- [PyPi](https://pypi.org/project/tables) (📥 680K / month):
	```
	pip install tables
	```
- [Conda](https://anaconda.org/conda-forge/pytables) (📥 2.5M · ⏱️ 14.01.2021):
	```
	conda install -c conda-forge pytables
	```
</details>
<details><summary><b><a href="https://github.com/Blosc/bcolz">bcolz</a></b> (🥉24 ·  ⭐ 910 · 💤) - A columnar data container that can be compressed. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/Blosc/bcolz) (👨‍💻 33 · 🔀 120 · 📦 1.6K · 📋 240 - 49% open · ⏱️ 10.09.2020):

	```
	git clone https://github.com/Blosc/bcolz
	```
- [PyPi](https://pypi.org/project/bcolz) (📥 29K / month):
	```
	pip install bcolz
	```
- [Conda](https://anaconda.org/conda-forge/bcolz) (📥 240K · ⏱️ 05.11.2019):
	```
	conda install -c conda-forge bcolz
	```
</details>
<details><summary><b><a href="https://github.com/vaexio/vaex">Vaex</a></b> (🥉22 ·  ⭐ 6.1K) - Out-of-Core hybrid Apache Arrow/NumPy DataFrame for Python, ML, visualize and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/vaexio/vaex) (👨‍💻 41 · 🔀 460 · 📥 200 · 📋 710 - 38% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/vaexio/vaex
	```
- [PyPi](https://pypi.org/project/vaex) (📥 11K / month):
	```
	pip install vaex
	```
- [Conda](https://anaconda.org/conda-forge/vaex) (📥 100K · ⏱️ 09.03.2021):
	```
	conda install -c conda-forge vaex
	```
</details>
<details><summary><b><a href="https://github.com/InvestmentSystems/static-frame">StaticFrame</a></b> (🥉21 ·  ⭐ 220) - Immutable and grow-only Pandas-like DataFrames with a more explicit.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/InvestmentSystems/static-frame) (👨‍💻 16 · 🔀 22 · 📦 6 · 📋 300 - 8% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/InvestmentSystems/static-frame
	```
- [PyPi](https://pypi.org/project/static-frame) (📥 1.6K / month):
	```
	pip install static-frame
	```
- [Conda](https://anaconda.org/conda-forge/static-frame) (📥 81K · ⏱️ 26.04.2021):
	```
	conda install -c conda-forge static-frame
	```
</details>
<details><summary><b><a href="https://github.com/xhochy/fletcher">fletcher</a></b> (🥉21 ·  ⭐ 210) - Pandas ExtensionDType/Array backed by Apache Arrow. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/xhochy/fletcher) (👨‍💻 24 · 🔀 31 · 📥 12 · 📦 3 · 📋 71 - 43% open · ⏱️ 18.02.2021):

	```
	git clone https://github.com/xhochy/fletcher
	```
- [PyPi](https://pypi.org/project/fletcher) (📥 550 / month):
	```
	pip install fletcher
	```
- [Conda](https://anaconda.org/conda-forge/fletcher) (📥 23K · ⏱️ 17.01.2021):
	```
	conda install -c conda-forge fletcher
	```
</details>
<details><summary><b><a href="https://github.com/h2oai/datatable">datatable</a></b> (🥉20 ·  ⭐ 1.2K) - A Python package for manipulating 2-dimensional tabular data.. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code></summary>

- [GitHub](https://github.com/h2oai/datatable) (👨‍💻 28 · 🔀 100 · 📥 980 · 📋 1.3K - 10% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/h2oai/datatable
	```
- [PyPi](https://pypi.org/project/datatable) (📥 28K / month):
	```
	pip install datatable
	```
</details>
<details><summary><b><a href="https://github.com/yhat/pandasql">pandasql</a></b> (🥉20 ·  ⭐ 970 · 💀) - sqldf for pandas. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/yhat/pandasql) (👨‍💻 15 · 🔀 140 · 📦 720 · 📋 63 - 63% open · ⏱️ 01.02.2017):

	```
	git clone https://github.com/yhat/pandasql
	```
- [PyPi](https://pypi.org/project/pandasql) (📥 330K / month):
	```
	pip install pandasql
	```
</details>
<details><summary><b><a href="https://github.com/patx/pickledb">pickleDB</a></b> (🥉20 ·  ⭐ 560 · 💀) - pickleDB is an open source key-value store using Python's json.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/patx/pickledb) (👨‍💻 11 · 🔀 99 · 📦 570 · 📋 50 - 22% open · ⏱️ 15.11.2019):

	```
	git clone https://github.com/patx/pickledb
	```
- [PyPi](https://pypi.org/project/pickledb) (📥 8.3K / month):
	```
	pip install pickledb
	```
</details>
<details><summary><b><a href="https://github.com/mouradmourafiq/pandas-summary">Pandas Summary</a></b> (🥉19 ·  ⭐ 360 · 💀) - An extension to pandas dataframes describe function. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/mouradmourafiq/pandas-summary) (👨‍💻 6 · 🔀 35 · 📦 600 · 📋 13 - 61% open · ⏱️ 24.08.2019):

	```
	git clone https://github.com/mouradmourafiq/pandas-summary
	```
- [PyPi](https://pypi.org/project/pandas-summary) (📥 32K / month):
	```
	pip install pandas-summary
	```
</details>
<details><summary><b><a href="https://github.com/RaRe-Technologies/bounter">Bounter</a></b> (🥉18 ·  ⭐ 900 · 💤) - Efficient Counter that uses a limited (bounded) amount of memory.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/RaRe-Technologies/bounter) (👨‍💻 8 · 🔀 46 · 📦 22 · 📋 20 - 55% open · ⏱️ 16.08.2020):

	```
	git clone https://github.com/RaRe-Technologies/bounter
	```
- [PyPi](https://pypi.org/project/bounter) (📥 250 / month):
	```
	pip install bounter
	```
</details>
<details><summary><b><a href="https://github.com/firmai/pandapy">PandaPy</a></b> (🥉12 ·  ⭐ 470) - PandaPy has the speed of NumPy and the usability of Pandas.. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/firmai/pandapy) (👨‍💻 3 · 🔀 47 · 📦 1 · 📋 2 - 50% open · ⏱️ 12.11.2020):

	```
	git clone https://github.com/firmai/pandapy
	```
- [PyPi](https://pypi.org/project/pandapy) (📥 160 / month):
	```
	pip install pandapy
	```
</details>
<br>

## Data Loading & Extraction

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for loading, collecting, and extracting data from a variety of data sources and formats._

<details><summary><b><a href="https://github.com/joke2k/faker">Faker</a></b> (🥇37 ·  ⭐ 12K) - Faker is a Python package that generates fake data for you. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/joke2k/faker) (👨‍💻 400 · 🔀 1.4K · 📦 26K · 📋 470 - 22% open · ⏱️ 23.04.2021):

	```
	git clone https://github.com/joke2k/faker
	```
- [PyPi](https://pypi.org/project/Faker) (📥 4.1M / month):
	```
	pip install Faker
	```
- [Conda](https://anaconda.org/conda-forge/faker) (📥 420K · ⏱️ 23.04.2021):
	```
	conda install -c conda-forge faker
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/datasets">TensorFlow Datasets</a></b> (🥇34 ·  ⭐ 2.8K) - TFDS is a collection of datasets ready to use with.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/datasets) (👨‍💻 200 · 🔀 980 · 📦 4.4K · 📋 830 - 32% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/tensorflow/datasets
	```
- [PyPi](https://pypi.org/project/tensorflow-datasets) (📥 4.8M / month):
	```
	pip install tensorflow-datasets
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/tablib">Tablib</a></b> (🥇32 ·  ⭐ 3.9K) - Python Module for Tabular Datasets in XLS, CSV, JSON, YAML, &c. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jazzband/tablib) (👨‍💻 110 · 🔀 550 · 📦 10K · 📋 220 - 12% open · ⏱️ 01.03.2021):

	```
	git clone https://github.com/jazzband/tablib
	```
- [PyPi](https://pypi.org/project/tablib) (📥 1.1M / month):
	```
	pip install tablib
	```
- [Conda](https://anaconda.org/conda-forge/tablib) (📥 61K · ⏱️ 05.12.2020):
	```
	conda install -c conda-forge tablib
	```
</details>
<details><summary><b><a href="https://github.com/martinblech/xmltodict">xmltodict</a></b> (🥈31 ·  ⭐ 4.4K · 💤) - Python module that makes working with XML feel like you are.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/martinblech/xmltodict) (👨‍💻 41 · 🔀 400 · 📦 24K · 📋 190 - 28% open · ⏱️ 26.04.2020):

	```
	git clone https://github.com/martinblech/xmltodict
	```
- [PyPi](https://pypi.org/project/xmltodict) (📥 8.7M / month):
	```
	pip install xmltodict
	```
- [Conda](https://anaconda.org/conda-forge/xmltodict) (📥 830K · ⏱️ 11.02.2019):
	```
	conda install -c conda-forge xmltodict
	```
</details>
<details><summary><b><a href="https://github.com/huggingface/datasets">Datasets</a></b> (🥈30 ·  ⭐ 7.3K) - The largest hub of ready-to-use NLP datasets for ML models with.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/huggingface/datasets) (👨‍💻 260 · 🔀 840 · 📦 650 · 📋 680 - 34% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/huggingface/datasets
	```
- [PyPi](https://pypi.org/project/datasets) (📥 120K / month):
	```
	pip install datasets
	```
</details>
<details><summary><b><a href="https://github.com/snorkel-team/snorkel">snorkel</a></b> (🥈28 ·  ⭐ 4.6K) - A system for quickly generating training data with weak supervision. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/snorkel-team/snorkel) (👨‍💻 64 · 🔀 730 · 📥 670 · 📦 81 · 📋 940 - 2% open · ⏱️ 13.03.2021):

	```
	git clone https://github.com/snorkel-team/snorkel
	```
- [PyPi](https://pypi.org/project/snorkel) (📥 120K / month):
	```
	pip install snorkel
	```
- [Conda](https://anaconda.org/conda-forge/snorkel) (📥 18K · ⏱️ 16.03.2021):
	```
	conda install -c conda-forge snorkel
	```
</details>
<details><summary><b><a href="https://github.com/python-excel/xlrd">xlrd</a></b> (🥈28 ·  ⭐ 1.9K) - Please use openpyxl where you can... <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/python-excel/xlrd) (👨‍💻 50 · 🔀 400 · 📦 70K · ⏱️ 12.12.2020):

	```
	git clone https://github.com/python-excel/xlrd
	```
- [PyPi](https://pypi.org/project/xlrd) (📥 9.4M / month):
	```
	pip install xlrd
	```
- [Conda](https://anaconda.org/conda-forge/xlrd) (📥 1.4M · ⏱️ 09.01.2021):
	```
	conda install -c conda-forge xlrd
	```
</details>
<details><summary><b><a href="https://github.com/euske/pdfminer">PDFMiner</a></b> (🥈27 ·  ⭐ 4.6K · 💀) - Python PDF Parser (Not actively maintained). Check out pdfminer.six. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/euske/pdfminer) (👨‍💻 28 · 🔀 940 · 📦 2.2K · 📋 230 - 82% open · ⏱️ 18.01.2020):

	```
	git clone https://github.com/euske/pdfminer
	```
- [PyPi](https://pypi.org/project/pdfminer) (📥 180K / month):
	```
	pip install pdfminer
	```
- [Conda](https://anaconda.org/conda-forge/pdfminer) (📥 16K · ⏱️ 15.02.2021):
	```
	conda install -c conda-forge pdfminer
	```
</details>
<details><summary><b><a href="https://github.com/wireservice/csvkit">csvkit</a></b> (🥈27 ·  ⭐ 4.6K) - A suite of utilities for converting to and working with CSV, the king of.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/wireservice/csvkit) (👨‍💻 92 · 🔀 530 · 📦 860 · 📋 810 - 7% open · ⏱️ 10.03.2021):

	```
	git clone https://github.com/wireservice/csvkit
	```
- [PyPi](https://pypi.org/project/csvkit) (📥 51K / month):
	```
	pip install csvkit
	```
- [Conda](https://anaconda.org/conda-forge/csvkit) (📥 49K · ⏱️ 28.05.2019):
	```
	conda install -c conda-forge csvkit
	```
</details>
<details><summary><b><a href="https://github.com/pydata/pandas-datareader">pandas-datareader</a></b> (🥈27 ·  ⭐ 2K) - Extract data from a wide range of Internet sources.. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pydata/pandas-datareader) (👨‍💻 77 · 🔀 510 · 📦 9K · 📋 450 - 17% open · ⏱️ 31.12.2020):

	```
	git clone https://github.com/pydata/pandas-datareader
	```
- [PyPi](https://pypi.org/project/pandas-datareader) (📥 230K / month):
	```
	pip install pandas-datareader
	```
- [Conda](https://anaconda.org/conda-forge/pandas-datareader) (📥 120K · ⏱️ 16.03.2021):
	```
	conda install -c conda-forge pandas-datareader
	```
</details>
<details><summary><b><a href="https://github.com/ahupp/python-magic">python-magic</a></b> (🥈27 ·  ⭐ 1.9K) - A python wrapper for libmagic. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/ahupp/python-magic) (👨‍💻 50 · 🔀 210 · 📦 14K · 📋 160 - 15% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/ahupp/python-magic
	```
- [PyPi](https://pypi.org/project/python-magic) (📥 2.5M / month):
	```
	pip install python-magic
	```
- [Conda](https://anaconda.org/conda-forge/python-magic) (📥 86K · ⏱️ 05.03.2021):
	```
	conda install -c conda-forge python-magic
	```
</details>
<details><summary><b><a href="https://github.com/RaRe-Technologies/smart_open">smart-open</a></b> (🥉26 ·  ⭐ 2K) - Utils for streaming large files (S3, HDFS, gzip, bz2...). <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/RaRe-Technologies/smart_open) (👨‍💻 79 · 🔀 270 · 📋 300 - 18% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/RaRe-Technologies/smart_open
	```
- [PyPi](https://pypi.org/project/smart-open) (📥 11M / month):
	```
	pip install smart-open
	```
</details>
<details><summary><b><a href="https://github.com/frictionlessdata/tabulator-py">tabulator-py</a></b> (🥉26 ·  ⭐ 200) - Python library for reading and writing tabular data via streams. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/frictionlessdata/tabulator-py) (👨‍💻 25 · 🔀 40 · 📦 520 · 📋 180 - 0% open · ⏱️ 22.03.2021):

	```
	git clone https://github.com/frictionlessdata/tabulator-py
	```
- [PyPi](https://pypi.org/project/tabulator) (📥 210K / month):
	```
	pip install tabulator
	```
- [Conda](https://anaconda.org/conda-forge/tabulator-py) (📥 41K · ⏱️ 24.07.2018):
	```
	conda install -c conda-forge tabulator-py
	```
</details>
<details><summary><b><a href="https://github.com/intake/intake">Intake</a></b> (🥉24 ·  ⭐ 550) - Intake is a lightweight package for finding, investigating, loading and.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/intake/intake) (👨‍💻 60 · 🔀 99 · 📦 250 · 📋 260 - 25% open · ⏱️ 22.04.2021):

	```
	git clone https://github.com/intake/intake
	```
- [PyPi](https://pypi.org/project/intake) (📥 9.5K / month):
	```
	pip install intake
	```
- [Conda](https://anaconda.org/conda-forge/intake) (📥 73K · ⏱️ 16.03.2021):
	```
	conda install -c conda-forge intake
	```
</details>
<details><summary><b><a href="https://github.com/deanmalmgren/textract">textract</a></b> (🥉22 ·  ⭐ 3K · 💀) - extract text from any document. no muss. no fuss. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/deanmalmgren/textract) (👨‍💻 30 · 🔀 410 · 📋 190 - 37% open · ⏱️ 14.11.2019):

	```
	git clone https://github.com/deanmalmgren/textract
	```
- [PyPi](https://pypi.org/project/textract) (📥 43K / month):
	```
	pip install textract
	```
- [Conda](https://anaconda.org/conda-forge/textract) (📥 11K · ⏱️ 20.03.2017):
	```
	conda install -c conda-forge textract
	```
</details>
<details><summary><b><a href="https://github.com/sdv-dev/SDV">SDV</a></b> (🥉22 ·  ⭐ 400) - Synthetic Data Generation for tabular, relational and time series data. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/sdv-dev/SDV) (👨‍💻 33 · 🔀 71 · 📦 21 · 📋 250 - 27% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/sdv-dev/SDV
	```
- [PyPi](https://pypi.org/project/sdv) (📥 6.4K / month):
	```
	pip install sdv
	```
</details>
<details><summary><b><a href="https://github.com/turicas/rows">rows</a></b> (🥉21 ·  ⭐ 750) - A common, beautiful interface to tabular data, no matter the format. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code></summary>

- [GitHub](https://github.com/turicas/rows) (👨‍💻 30 · 🔀 130 · 📥 37 · 📦 120 · 📋 290 - 48% open · ⏱️ 11.03.2021):

	```
	git clone https://github.com/turicas/rows
	```
- [PyPi](https://pypi.org/project/rows) (📥 1.8K / month):
	```
	pip install rows
	```
</details>
<details><summary><b><a href="https://github.com/okfn/messytables">messytables</a></b> (🥉20 ·  ⭐ 360 · 💀) - Tools for parsing messy tabular data. This is now.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/okfn/messytables) (👨‍💻 44 · 🔀 100 · 📦 190 · 📋 85 - 35% open · ⏱️ 13.11.2019):

	```
	git clone https://github.com/okfn/messytables
	```
- [PyPi](https://pypi.org/project/messytables) (📥 7K / month):
	```
	pip install messytables
	```
</details>
<details><summary><b><a href="https://github.com/pyexcel/pyexcel-xlsx">pyexcel-xlsx</a></b> (🥉20 ·  ⭐ 88) - A wrapper library to read, manipulate and write data in.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/pyexcel/pyexcel-xlsx) (👨‍💻 4 · 🔀 16 · 📥 46 · 📦 1.2K · 📋 32 - 37% open · ⏱️ 28.11.2020):

	```
	git clone https://github.com/pyexcel/pyexcel-xlsx
	```
- [PyPi](https://pypi.org/project/pyexcel-xlsx) (📥 84K / month):
	```
	pip install pyexcel-xlsx
	```
- [Conda](https://anaconda.org/conda-forge/pyexcel-xlsx) (📥 16K · ⏱️ 10.10.2020):
	```
	conda install -c conda-forge pyexcel-xlsx
	```
</details>
<details><summary><b><a href="https://github.com/shawnbrown/datatest">datatest</a></b> (🥉19 ·  ⭐ 240) - Tools for test driven data-wrangling and data validation. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/shawnbrown/datatest) (👨‍💻 6 · 🔀 12 · 📦 31 · 📋 51 - 17% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/shawnbrown/datatest
	```
- [PyPi](https://pypi.org/project/datatest) (📥 6.5K / month):
	```
	pip install datatest
	```
</details>
<details><summary><b><a href="https://github.com/atlanhq/camelot">Camelot</a></b> (🥉18 ·  ⭐ 3K · 💀) - Camelot: PDF Table Extraction for Humans. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/atlanhq/camelot) (👨‍💻 23 · 🔀 310 · 📋 340 - 18% open · ⏱️ 15.10.2019):

	```
	git clone https://github.com/atlanhq/camelot
	```
- [PyPi](https://pypi.org/project/camelot-py) (📥 28K / month):
	```
	pip install camelot-py
	```
</details>
<details><summary><b><a href="https://github.com/singer-io/getting-started">Singer</a></b> (🥉18 ·  ⭐ 760) - Standard for moving data between databases, web APIs, files, queues,.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/singer-io/getting-started) (👨‍💻 26 · 🔀 100 · 📋 33 - 45% open · ⏱️ 14.04.2021):

	```
	git clone https://github.com/singer-io/getting-started
	```
- [PyPi](https://pypi.org/project/singer-python) (📥 83K / month):
	```
	pip install singer-python
	```
</details>
<details><summary><b><a href="https://foss.heptapod.net/openpyxl/openpyxl">openpyxl</a></b> (🥉14 ·  ⭐ 19) - A Python library to read/write Excel 2010 xlsx/xlsm files. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [PyPi](https://pypi.org/project/openpyxl) (📥 11M / month):
	```
	pip install openpyxl
	```
- [GitLab](https://foss.heptapod.net/openpyxl/openpyxl) (🔀 0 · 📋 1.7K - 11% open · ⏱️ 13.03.2021):

	```
	git clone https://foss.heptapod.net/openpyxl/openpyxl
	```
- [Conda](https://anaconda.org/anaconda/openpyxl) (📥 48K · ⏱️ 13.03.2021):
	```
	conda install -c anaconda openpyxl
	```
- [Docker Hub](https://hub.docker.com/r/openpyxl/openpyxl-ci) (📥 1.2K · ⏱️ 13.09.2018):
	```
	docker pull openpyxl/openpyxl-ci
	```
</details>
<br>

## Web Scraping & Crawling

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for web scraping, crawling, downloading, and mining as well as libraries._

🔗&nbsp;<b><a href="https://github.com/ml-tooling/best-of-web-python">Python Web Scraping</a></b> ( ⭐ 1.2K · 🐣)  - Collection of web-scraping and crawling libraries.

<br>

## Data Pipelines & Streaming

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for data batch- and stream-processing, workflow automation, job scheduling, and other data pipeline tasks._

<details><summary><b><a href="https://github.com/celery/celery">Celery</a></b> (🥇36 ·  ⭐ 17K) - Asynchronous task queue/job queue based on distributed message.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/celery/celery) (👨‍💻 1.1K · 🔀 3.8K · 📦 52K · 📋 4.4K - 10% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/celery/celery
	```
- [PyPi](https://pypi.org/project/celery) (📥 5M / month):
	```
	pip install celery
	```
- [Conda](https://anaconda.org/conda-forge/celery) (📥 470K · ⏱️ 24.03.2021):
	```
	conda install -c conda-forge celery
	```
</details>
<details><summary><b><a href="https://github.com/spotify/luigi">luigi</a></b> (🥇34 ·  ⭐ 14K) - Luigi is a Python module that helps you build complex pipelines of batch.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/spotify/luigi) (👨‍💻 560 · 🔀 2.2K · 📦 1.4K · 📋 900 - 5% open · ⏱️ 16.04.2021):

	```
	git clone https://github.com/spotify/luigi
	```
- [PyPi](https://pypi.org/project/luigi) (📥 840K / month):
	```
	pip install luigi
	```
- [Conda](https://anaconda.org/anaconda/luigi) (📥 7K · ⏱️ 17.04.2021):
	```
	conda install -c anaconda luigi
	```
</details>
<details><summary><b><a href="https://github.com/joblib/joblib">joblib</a></b> (🥇34 ·  ⭐ 2.4K) - Computing with Python functions. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/joblib/joblib) (👨‍💻 99 · 🔀 280 · 📦 97K · 📋 620 - 41% open · ⏱️ 02.04.2021):

	```
	git clone https://github.com/joblib/joblib
	```
- [PyPi](https://pypi.org/project/joblib) (📥 28M / month):
	```
	pip install joblib
	```
- [Conda](https://anaconda.org/conda-forge/joblib) (📥 3.9M · ⏱️ 09.02.2021):
	```
	conda install -c conda-forge joblib
	```
</details>
<details><summary><b><a href="https://github.com/rq/rq">rq</a></b> (🥇32 ·  ⭐ 7.7K) - Simple job queues for Python. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/rq/rq) (👨‍💻 230 · 🔀 1.2K · 📦 7.8K · 📋 840 - 16% open · ⏱️ 20.04.2021):

	```
	git clone https://github.com/rq/rq
	```
- [PyPi](https://pypi.org/project/rq) (📥 490K / month):
	```
	pip install rq
	```
- [Conda](https://anaconda.org/conda-forge/rq) (📥 50K · ⏱️ 31.03.2021):
	```
	conda install -c conda-forge rq
	```
</details>
<details><summary><b><a href="https://github.com/apache/airflow">Airflow</a></b> (🥈31 ·  ⭐ 22K) - Platform to programmatically author, schedule, and monitor workflows. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/apache/airflow) (👨‍💻 1.8K · 🔀 8.1K · 📥 120K · 📋 3.2K - 24% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/apache/airflow
	```
- [PyPi](https://pypi.org/project/apache-airflow) (📥 1.8M / month):
	```
	pip install apache-airflow
	```
- [Conda](https://anaconda.org/conda-forge/airflow) (📥 310K · ⏱️ 20.04.2021):
	```
	conda install -c conda-forge airflow
	```
- [Docker Hub](https://hub.docker.com/r/apache/airflow) (📥 19M · ⭐ 240 · ⏱️ 27.04.2021):
	```
	docker pull apache/airflow
	```
</details>
<details><summary><b><a href="https://github.com/PrefectHQ/prefect">Prefect</a></b> (🥈31 ·  ⭐ 6.1K) - The easiest way to automate your data. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/PrefectHQ/prefect) (👨‍💻 200 · 🔀 550 · 📦 310 · 📋 1.7K - 16% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/PrefectHQ/prefect
	```
- [PyPi](https://pypi.org/project/prefect) (📥 76K / month):
	```
	pip install prefect
	```
- [Conda](https://anaconda.org/conda-forge/prefect) (📥 91K · ⏱️ 14.04.2021):
	```
	conda install -c conda-forge prefect
	```
</details>
<details><summary><b><a href="https://github.com/apache/beam">Beam</a></b> (🥈29 ·  ⭐ 4.7K) - Unified programming model to define and execute data processing.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/apache/beam) (👨‍💻 1K · 🔀 2.9K · ⏱️ 28.04.2021):

	```
	git clone https://github.com/apache/beam
	```
- [PyPi](https://pypi.org/project/apache-beam) (📥 2.4M / month):
	```
	pip install apache-beam
	```
</details>
<details><summary><b><a href="https://github.com/fishtown-analytics/dbt">dbt</a></b> (🥈29 ·  ⭐ 2.9K) - dbt (data build tool) enables data analysts and engineers to transform.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/fishtown-analytics/dbt) (👨‍💻 140 · 🔀 560 · 📦 260 · 📋 1.9K - 17% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/fishtown-analytics/dbt
	```
- [PyPi](https://pypi.org/project/dbt) (📥 320K / month):
	```
	pip install dbt
	```
- [Conda](https://anaconda.org/conda-forge/dbt) (📥 160K · ⏱️ 14.05.2020):
	```
	conda install -c conda-forge dbt
	```
</details>
<details><summary><b><a href="https://github.com/dagster-io/dagster">Dagster</a></b> (🥈28 ·  ⭐ 3.2K) - A data orchestrator for machine learning, analytics, and ETL. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/dagster-io/dagster) (👨‍💻 130 · 🔀 340 · 📦 160 · 📋 2.8K - 19% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/dagster-io/dagster
	```
- [PyPi](https://pypi.org/project/dagster) (📥 53K / month):
	```
	pip install dagster
	```
- [Conda](https://anaconda.org/conda-forge/dagster) (📥 220K · ⏱️ 26.04.2021):
	```
	conda install -c conda-forge dagster
	```
</details>
<details><summary><b><a href="https://github.com/Yelp/mrjob">mrjob</a></b> (🥈28 ·  ⭐ 2.5K) - Run MapReduce jobs on Hadoop or Amazon Web Services. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Yelp/mrjob) (👨‍💻 140 · 🔀 560 · 📦 720 · 📋 1.3K - 15% open · ⏱️ 16.11.2020):

	```
	git clone https://github.com/Yelp/mrjob
	```
- [PyPi](https://pypi.org/project/mrjob) (📥 99K / month):
	```
	pip install mrjob
	```
- [Conda](https://anaconda.org/conda-forge/mrjob) (📥 350K · ⏱️ 24.12.2020):
	```
	conda install -c conda-forge mrjob
	```
</details>
<details><summary><b><a href="https://github.com/quantumblacklabs/kedro">Kedro</a></b> (🥈27 ·  ⭐ 3.8K) - A Python framework for creating reproducible, maintainable and.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/quantumblacklabs/kedro) (👨‍💻 100 · 🔀 440 · 📦 460 · 📋 460 - 8% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/quantumblacklabs/kedro
	```
- [PyPi](https://pypi.org/project/kedro) (📥 130K / month):
	```
	pip install kedro
	```
</details>
<details><summary><b><a href="https://github.com/EntilZha/PyFunctional">PyFunctional</a></b> (🥈27 ·  ⭐ 1.8K) - Python library for creating data pipelines with chain functional.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/EntilZha/PyFunctional) (👨‍💻 23 · 🔀 98 · 📦 280 · 📋 120 - 2% open · ⏱️ 03.03.2021):

	```
	git clone https://github.com/EntilZha/PyFunctional
	```
- [PyPi](https://pypi.org/project/pyfunctional) (📥 73K / month):
	```
	pip install pyfunctional
	```
</details>
<details><summary><b><a href="https://github.com/petl-developers/petl">petl</a></b> (🥈27 ·  ⭐ 880) - Python Extract Transform and Load Tables of Data. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/petl-developers/petl) (👨‍💻 46 · 🔀 150 · 📦 380 · 📋 410 - 16% open · ⏱️ 17.04.2021):

	```
	git clone https://github.com/petl-developers/petl
	```
- [PyPi](https://pypi.org/project/petl) (📥 34K / month):
	```
	pip install petl
	```
- [Conda](https://anaconda.org/conda-forge/petl) (📥 23K · ⏱️ 05.04.2021):
	```
	conda install -c conda-forge petl
	```
</details>
<details><summary><b><a href="https://github.com/robinhood/faust">faust</a></b> (🥈26 ·  ⭐ 5.5K) - Python Stream Processing. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/robinhood/faust) (👨‍💻 91 · 🔀 450 · 📦 720 · 📋 420 - 46% open · ⏱️ 09.10.2020):

	```
	git clone https://github.com/robinhood/faust
	```
- [PyPi](https://pypi.org/project/faust) (📥 820K / month):
	```
	pip install faust
	```
</details>
<details><summary><b><a href="https://github.com/activeloopai/Hub">Hub</a></b> (🥈26 ·  ⭐ 3.2K) - Fastest unstructured dataset management for TensorFlow/PyTorch... <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/activeloopai/Hub) (👨‍💻 76 · 🔀 240 · 📦 120 · 📋 250 - 6% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/activeloopai/Hub
	```
- [PyPi](https://pypi.org/project/hub) (📥 3.1K / month):
	```
	pip install hub
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/tfx">TFX</a></b> (🥉25 ·  ⭐ 1.4K) - TFX is an end-to-end platform for deploying production ML pipelines. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/tfx) (👨‍💻 110 · 🔀 420 · 📋 560 - 36% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/tensorflow/tfx
	```
- [PyPi](https://pypi.org/project/tfx) (📥 230K / month):
	```
	pip install tfx
	```
</details>
<details><summary><b><a href="https://github.com/great-expectations/great_expectations">Great Expectations</a></b> (🥉24 ·  ⭐ 4.3K) - Always know what to expect from your data. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/great-expectations/great_expectations) (👨‍💻 180 · 🔀 530 · 📋 820 - 22% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/great-expectations/great_expectations
	```
- [PyPi](https://pypi.org/project/great_expectations) (📥 640K / month):
	```
	pip install great_expectations
	```
</details>
<details><summary><b><a href="https://github.com/ironmussa/Optimus">Optimus</a></b> (🥉23 ·  ⭐ 1K · 📉) - Agile Data Preparation Workflows madeeasy with pandas, dask,.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/ironmussa/Optimus) (👨‍💻 21 · 🔀 190 · 📦 14 · 📋 200 - 16% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/ironmussa/Optimus
	```
- [PyPi](https://pypi.org/project/optimuspyspark) (📥 8.1K / month):
	```
	pip install optimuspyspark
	```
</details>
<details><summary><b><a href="https://github.com/python-bonobo/bonobo">bonobo</a></b> (🥉22 ·  ⭐ 1.4K) - Extract Transform Load for Python 3.5+. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/python-bonobo/bonobo) (👨‍💻 37 · 🔀 120 · 📦 110 · 📋 180 - 38% open · ⏱️ 10.03.2021):

	```
	git clone https://github.com/python-bonobo/bonobo
	```
- [PyPi](https://pypi.org/project/bonobo) (📥 9.5K / month):
	```
	pip install bonobo
	```
</details>
<details><summary><b><a href="https://github.com/svenkreiss/pysparkling">pysparkling</a></b> (🥉22 ·  ⭐ 230) - A pure Python implementation of Apache Spark's RDD and.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/svenkreiss/pysparkling) (👨‍💻 10 · 🔀 39 · 📦 62 · 📋 27 - 22% open · ⏱️ 22.02.2021):

	```
	git clone https://github.com/svenkreiss/pysparkling
	```
- [PyPi](https://pypi.org/project/pysparkling) (📥 13K / month):
	```
	pip install pysparkling
	```
</details>
<details><summary><b><a href="https://github.com/douban/dpark">dpark</a></b> (🥉21 ·  ⭐ 2.7K) - Python clone of Spark, a MapReduce alike framework in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/douban/dpark) (👨‍💻 35 · 🔀 540 · 📦 3 · ⏱️ 25.12.2020):

	```
	git clone https://github.com/douban/dpark
	```
- [PyPi](https://pypi.org/project/dpark) (📥 200 / month):
	```
	pip install dpark
	```
</details>
<details><summary><b><a href="https://github.com/Parsely/streamparse">streamparse</a></b> (🥉21 ·  ⭐ 1.4K) - Run Python in Apache Storm topologies. Pythonic API, CLI.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/Parsely/streamparse) (👨‍💻 40 · 🔀 210 · 📦 48 · 📋 320 - 18% open · ⏱️ 18.12.2020):

	```
	git clone https://github.com/Parsely/streamparse
	```
- [PyPi](https://pypi.org/project/streamparse) (📥 2.9K / month):
	```
	pip install streamparse
	```
</details>
<details><summary><b><a href="https://github.com/cgarciae/pypeln">Pypeline</a></b> (🥉21 ·  ⭐ 1.2K) - Concurrent data pipelines in Python . <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/cgarciae/pypeln) (👨‍💻 10 · 🔀 69 · 📋 49 - 26% open · ⏱️ 13.04.2021):

	```
	git clone https://github.com/cgarciae/pypeln
	```
- [PyPi](https://pypi.org/project/pypeln) (📥 26K / month):
	```
	pip install pypeln
	```
</details>
<details><summary><b><a href="https://github.com/pricingassistant/mrq">mrq</a></b> (🥉20 ·  ⭐ 840) - Mr. Queue - A distributed worker task queue in Python using Redis & gevent. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pricingassistant/mrq) (👨‍💻 37 · 🔀 110 · 📦 23 · 📋 170 - 30% open · ⏱️ 13.12.2020):

	```
	git clone https://github.com/pricingassistant/mrq
	```
- [PyPi](https://pypi.org/project/mrq) (📥 850 / month):
	```
	pip install mrq
	```
</details>
<details><summary><b><a href="https://github.com/closeio/tasktiger">TaskTiger</a></b> (🥉19 ·  ⭐ 1.1K) - Python task queue using Redis. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/closeio/tasktiger) (👨‍💻 20 · 🔀 56 · 📦 20 · 📋 56 - 42% open · ⏱️ 21.04.2021):

	```
	git clone https://github.com/closeio/tasktiger
	```
- [PyPi](https://pypi.org/project/tasktiger) (📥 940 / month):
	```
	pip install tasktiger
	```
</details>
<details><summary><b><a href="https://github.com/pdpipe/pdpipe">pdpipe</a></b> (🥉19 ·  ⭐ 600) - Easy pipelines for pandas DataFrames. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pdpipe/pdpipe) (👨‍💻 8 · 🔀 27 · 📦 29 · 📋 21 - 28% open · ⏱️ 23.02.2021):

	```
	git clone https://github.com/pdpipe/pdpipe
	```
- [PyPi](https://pypi.org/project/pdpipe) (📥 2.3K / month):
	```
	pip install pdpipe
	```
</details>
<details><summary><b><a href="https://github.com/mara/mara-pipelines">Mara Pipelines</a></b> (🥉18 ·  ⭐ 1.7K) - A lightweight opinionated ETL framework, halfway between plain.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mara/mara-pipelines) (👨‍💻 16 · 🔀 75 · 📦 7 · 📋 18 - 33% open · ⏱️ 08.03.2021):

	```
	git clone https://github.com/mara/mara-pipelines
	```
- [PyPi](https://pypi.org/project/mara-pipelines) (📥 180 / month):
	```
	pip install mara-pipelines
	```
</details>
<details><summary><b><a href="https://github.com/ploomber/ploomber">ploomber</a></b> (🥉18 ·  ⭐ 270) - Lean Data Science workflows: develop and test locally. Deploy to.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/ploomber/ploomber) (👨‍💻 4 · 🔀 4 · 📦 13 · 📋 290 - 13% open · ⏱️ 24.04.2021):

	```
	git clone https://github.com/ploomber/ploomber
	```
- [PyPi](https://pypi.org/project/ploomber) (📥 3K / month):
	```
	pip install ploomber
	```
</details>
<details><summary><b><a href="https://github.com/analysiscenter/batchflow">BatchFlow</a></b> (🥉18 ·  ⭐ 160) - BatchFlow helps you conveniently work with random or sequential.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/analysiscenter/batchflow) (👨‍💻 29 · 🔀 35 · 📋 99 - 35% open · ⏱️ 22.04.2021):

	```
	git clone https://github.com/analysiscenter/batchflow
	```
- [PyPi](https://pypi.org/project/batchflow) (📥 140 / month):
	```
	pip install batchflow
	```
</details>
<details><summary><b><a href="https://github.com/databricks/spark-deep-learning">spark-deep-learning</a></b> (🥉17 ·  ⭐ 1.8K) - Deep Learning Pipelines for Apache Spark. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/databricks/spark-deep-learning) (👨‍💻 15 · 🔀 440 · 📦 17 · 📋 100 - 73% open · ⏱️ 20.01.2021):

	```
	git clone https://github.com/databricks/spark-deep-learning
	```
</details>
<details><summary><b><a href="https://github.com/d6t/d6tflow">Databolt Flow</a></b> (🥉17 ·  ⭐ 910) - Python library for building highly effective data science workflows. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/d6t/d6tflow) (👨‍💻 12 · 🔀 66 · 📦 13 · 📋 20 - 40% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/d6t/d6tflow
	```
- [PyPi](https://pypi.org/project/d6tflow) (📥 390 / month):
	```
	pip install d6tflow
	```
</details>
<details><summary><b><a href="https://github.com/nerevu/riko">riko</a></b> (🥉16 ·  ⭐ 1.6K · 💤) - A Python stream processing engine modeled after Yahoo! Pipes. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nerevu/riko) (👨‍💻 18 · 🔀 64 · 📋 29 - 72% open · ⏱️ 14.08.2020):

	```
	git clone https://github.com/nerevu/riko
	```
- [PyPi](https://pypi.org/project/riko) (📥 500 / month):
	```
	pip install riko
	```
</details>
<details><summary><b><a href="https://github.com/maiot-io/zenml">zenml</a></b> (🥉16 ·  ⭐ 1.1K · 🐣) - ZenML : MLOps framework to create reproducible ML pipelines for.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/maiot-io/zenml) (👨‍💻 11 · 🔀 54 · 📦 1 · 📋 35 - 25% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/maiot-io/zenml
	```
- [PyPi](https://pypi.org/project/zenml) (📥 540 / month):
	```
	pip install zenml
	```
</details>
<details><summary><b><a href="https://github.com/olirice/flupy">flupy</a></b> (🥉14 ·  ⭐ 160) - Fluent data pipelines for python and your shell. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/olirice/flupy) (👨‍💻 4 · 🔀 9 · ⏱️ 09.03.2021):

	```
	git clone https://github.com/olirice/flupy
	```
- [PyPi](https://pypi.org/project/flupy) (📥 19K / month):
	```
	pip install flupy
	```
</details>
<details><summary><b><a href="https://github.com/kkyon/botflow">Botflow</a></b> (🥉12 ·  ⭐ 1.2K · 💀) - Python Fast Dataflow programming framework for Data pipeline.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/kkyon/botflow) (👨‍💻 11 · 🔀 99 · 📦 1 · 📋 4 - 50% open · ⏱️ 23.05.2019):

	```
	git clone https://github.com/kkyon/botflow
	```
- [PyPi](https://pypi.org/project/botflow) (📥 120 / month):
	```
	pip install botflow
	```
</details>
<details><summary><b><a href="https://github.com/bodywork-ml/bodywork-core">bodywork-core</a></b> (🥉10 ·  ⭐ 200 · 🐣) - MLOps tool for deploying machine learning projects to.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/bodywork-ml/bodywork-core) (👨‍💻 4 · 🔀 10 · 📦 1 · 📋 24 - 29% open · ⏱️ 25.04.2021):

	```
	git clone https://github.com/bodywork-ml/bodywork-core
	```
- [PyPi](https://pypi.org/project/bodywork-core):
	```
	pip install bodywork-core
	```
</details>
<br>

## Distributed Machine Learning

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries that provide capabilities to distribute and parallelize machine learning tasks across large-scale compute infrastructure._

<details><summary><b><a href="https://github.com/ray-project/ray">Ray</a></b> (🥇32 ·  ⭐ 16K) - An open source framework that provides a simple, universal API for.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/ray-project/ray) (👨‍💻 470 · 🔀 2.5K · 📦 2K · 📋 6.5K - 20% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/ray-project/ray
	```
- [PyPi](https://pypi.org/project/ray) (📥 390K / month):
	```
	pip install ray
	```
</details>
<details><summary><b><a href="https://github.com/dask/dask">dask</a></b> (🥇32 ·  ⭐ 8.3K) - Parallel computing with task scheduling. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/dask/dask) (👨‍💻 440 · 🔀 1.2K · 📦 27K · 📋 3.6K - 17% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/dask/dask
	```
- [PyPi](https://pypi.org/project/dask) (📥 4.5M / month):
	```
	pip install dask
	```
- [Conda](https://anaconda.org/conda-forge/dask) (📥 3.3M · ⏱️ 24.04.2021):
	```
	conda install -c conda-forge dask
	```
</details>
<details><summary><b><a href="https://github.com/dask/distributed">dask.distributed</a></b> (🥇28 ·  ⭐ 1.2K) - A distributed task scheduler for Dask. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/dask/distributed) (👨‍💻 240 · 🔀 510 · 📦 18K · 📋 2K - 33% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/dask/distributed
	```
- [PyPi](https://pypi.org/project/distributed) (📥 3.3M / month):
	```
	pip install distributed
	```
- [Conda](https://anaconda.org/conda-forge/distributed) (📥 4.2M · ⏱️ 23.04.2021):
	```
	conda install -c conda-forge distributed
	```
</details>
<details><summary><b><a href="https://github.com/horovod/horovod">horovod</a></b> (🥈27 ·  ⭐ 11K) - Distributed training framework for TensorFlow, Keras, PyTorch,.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/horovod/horovod) (👨‍💻 120 · 🔀 1.8K · 📦 350 · 📋 1.8K - 12% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/horovod/horovod
	```
- [PyPi](https://pypi.org/project/horovod) (📥 52K / month):
	```
	pip install horovod
	```
</details>
<details><summary><b><a href="https://github.com/DEAP/deap">DEAP</a></b> (🥈27 ·  ⭐ 4.2K) - Distributed Evolutionary Algorithms in Python. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code></summary>

- [GitHub](https://github.com/DEAP/deap) (👨‍💻 67 · 🔀 870 · 📦 1.8K · 📋 400 - 43% open · ⏱️ 25.12.2020):

	```
	git clone https://github.com/deap/deap
	```
- [PyPi](https://pypi.org/project/deap) (📥 120K / month):
	```
	pip install deap
	```
- [Conda](https://anaconda.org/conda-forge/deap) (📥 130K · ⏱️ 13.01.2021):
	```
	conda install -c conda-forge deap
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/mesh">Mesh</a></b> (🥈26 ·  ⭐ 990) - Mesh TensorFlow: Model Parallelism Made Easier. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/mesh) (👨‍💻 41 · 🔀 160 · 📦 520 · 📋 67 - 80% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/tensorflow/mesh
	```
- [PyPi](https://pypi.org/project/mesh-tensorflow) (📥 120K / month):
	```
	pip install mesh-tensorflow
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/DeepSpeed">DeepSpeed</a></b> (🥈25 ·  ⭐ 4.8K) - DeepSpeed is a deep learning optimization library that makes.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/microsoft/DeepSpeed) (👨‍💻 49 · 🔀 450 · 📦 26 · 📋 430 - 44% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/microsoft/DeepSpeed
	```
- [PyPi](https://pypi.org/project/deepspeed) (📥 40K / month):
	```
	pip install deepspeed
	```
- [Docker Hub](https://hub.docker.com/r/deepspeed/deepspeed) (📥 8.2K · ⭐ 2 · ⏱️ 20.02.2021):
	```
	docker pull deepspeed/deepspeed
	```
</details>
<details><summary><b><a href="https://github.com/intel-analytics/BigDL">BigDL</a></b> (🥈25 ·  ⭐ 3.7K) - BigDL: Distributed Deep Learning Framework for Apache Spark. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/intel-analytics/BigDL) (👨‍💻 72 · 🔀 840 · 📦 25 · 📋 880 - 17% open · ⏱️ 21.04.2021):

	```
	git clone https://github.com/intel-analytics/BigDL
	```
- [PyPi](https://pypi.org/project/bigdl) (📥 2.2K / month):
	```
	pip install bigdl
	```
- [Maven](https://search.maven.org/artifact/com.intel.analytics.bigdl/bigdl-SPARK_2.4):
	```
	<dependency>
		<groupId>com.intel.analytics.bigdl</groupId>
		<artifactId>bigdl-SPARK_2.4</artifactId>
		<version>[VERSION]</version>
	</dependency>
	```
</details>
<details><summary><b><a href="https://github.com/maxpumperla/elephas">Elephas</a></b> (🥈25 ·  ⭐ 1.5K) - Distributed Deep learning with Keras & Spark. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>keras</code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/maxpumperla/elephas) (👨‍💻 27 · 🔀 280 · 📦 40 · 📋 140 - 15% open · ⏱️ 21.04.2021):

	```
	git clone https://github.com/maxpumperla/elephas
	```
- [PyPi](https://pypi.org/project/elephas) (📥 15K / month):
	```
	pip install elephas
	```
</details>
<details><summary><b><a href="https://github.com/uber/petastorm">petastorm</a></b> (🥈25 ·  ⭐ 1.1K) - Petastorm library enables single machine or distributed training.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/uber/petastorm) (👨‍💻 38 · 🔀 190 · 📥 290 · 📦 29 · 📋 230 - 49% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/uber/petastorm
	```
- [PyPi](https://pypi.org/project/petastorm) (📥 94K / month):
	```
	pip install petastorm
	```
</details>
<details><summary><b><a href="https://github.com/yahoo/TensorFlowOnSpark">TensorFlowOnSpark</a></b> (🥈24 ·  ⭐ 3.7K) - TensorFlowOnSpark brings TensorFlow programs to.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/yahoo/TensorFlowOnSpark) (👨‍💻 33 · 🔀 910 · 📋 350 - 3% open · ⏱️ 29.03.2021):

	```
	git clone https://github.com/yahoo/TensorFlowOnSpark
	```
- [PyPi](https://pypi.org/project/tensorflowonspark) (📥 180K / month):
	```
	pip install tensorflowonspark
	```
</details>
<details><summary><b><a href="https://github.com/intel-analytics/analytics-zoo">analytics-zoo</a></b> (🥉23 ·  ⭐ 2.3K) - Distributed Tensorflow, Keras and PyTorch on Apache.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/intel-analytics/analytics-zoo) (👨‍💻 90 · 🔀 640 · 📦 2 · 📋 980 - 37% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/intel-analytics/analytics-zoo
	```
- [PyPi](https://pypi.org/project/analytics-zoo) (📥 2.1K / month):
	```
	pip install analytics-zoo
	```
</details>
<details><summary><b><a href="https://github.com/ipython/ipyparallel">ipyparallel</a></b> (🥉23 ·  ⭐ 1.9K) - Interactive Parallel Computing in Python. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/ipython/ipyparallel) (👨‍💻 97 · 🔀 750 · 📦 1.5K · 📋 250 - 57% open · ⏱️ 19.04.2021):

	```
	git clone https://github.com/ipython/ipyparallel
	```
- [PyPi](https://pypi.org/project/ipyparallel) (📥 180K / month):
	```
	pip install ipyparallel
	```
- [Conda](https://anaconda.org/conda-forge/ipyparallel) (📥 430K · ⏱️ 22.01.2021):
	```
	conda install -c conda-forge ipyparallel
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/fairscale">FairScale</a></b> (🥉23 ·  ⭐ 990) - PyTorch extensions for high performance and large scale training. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/fairscale) (👨‍💻 29 · 🔀 73 · 📦 15 · 📋 160 - 24% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/facebookresearch/fairscale
	```
- [PyPi](https://pypi.org/project/fairscale) (📥 19K / month):
	```
	pip install fairscale
	```
</details>
<details><summary><b><a href="https://github.com/dask/dask-ml">dask-ml</a></b> (🥉23 ·  ⭐ 700) - Scalable Machine Learning with Dask. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/dask/dask-ml) (👨‍💻 64 · 🔀 190 · 📦 380 · 📋 380 - 42% open · ⏱️ 17.04.2021):

	```
	git clone https://github.com/dask/dask-ml
	```
- [PyPi](https://pypi.org/project/dask-ml) (📥 71K / month):
	```
	pip install dask-ml
	```
- [Conda](https://anaconda.org/conda-forge/dask-ml) (📥 210K · ⏱️ 30.01.2021):
	```
	conda install -c conda-forge dask-ml
	```
</details>
<details><summary><b><a href="https://github.com/Azure/mmlspark">MMLSpark</a></b> (🥉22 ·  ⭐ 2.3K) - Microsoft Machine Learning for Apache Spark. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/Azure/mmlspark) (👨‍💻 64 · 🔀 490 · 📋 400 - 43% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/Azure/mmlspark
	```
- [PyPi](https://pypi.org/project/mmlspark) (📥 44K / month):
	```
	pip install mmlspark
	```
</details>
<details><summary><b><a href="https://github.com/facebookincubator/submitit">Submit it</a></b> (🥉21 ·  ⭐ 340) - Python 3.6+ toolbox for submitting jobs to Slurm. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebookincubator/submitit) (👨‍💻 11 · 🔀 21 · 📦 120 · 📋 33 - 30% open · ⏱️ 01.04.2021):

	```
	git clone https://github.com/facebookincubator/submitit
	```
- [PyPi](https://pypi.org/project/submitit) (📥 5K / month):
	```
	pip install submitit
	```
- [Conda](https://anaconda.org/conda-forge/submitit) (📥 2.4K · ⏱️ 10.02.2021):
	```
	conda install -c conda-forge submitit
	```
</details>
<details><summary><b><a href="https://github.com/apache/singa">Apache Singa</a></b> (🥉19 ·  ⭐ 2.2K) - a distributed deep learning platform. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/apache/singa) (👨‍💻 70 · 🔀 600 · 📦 1 · 📋 52 - 32% open · ⏱️ 15.01.2021):

	```
	git clone https://github.com/apache/singa
	```
- [Conda](https://anaconda.org/nusdbsystem/singa) (📥 270 · ⏱️ 20.01.2021):
	```
	conda install -c nusdbsystem singa
	```
- [Docker Hub](https://hub.docker.com/r/apache/singa) (📥 160 · ⭐ 2 · ⏱️ 04.06.2019):
	```
	docker pull apache/singa
	```
</details>
<details><summary><b><a href="https://github.com/databricks/tensorframes">TensorFrames</a></b> (🥉19 ·  ⭐ 770 · 💀) - [DEPRECATED] Tensorflow wrapper for DataFrames on.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/databricks/tensorframes) (👨‍💻 16 · 🔀 160 · 📋 91 - 52% open · ⏱️ 15.11.2019):

	```
	git clone https://github.com/databricks/tensorframes
	```
- [PyPi](https://pypi.org/project/tensorframes) (📥 11K / month):
	```
	pip install tensorframes
	```
</details>
<details><summary><b><a href="https://github.com/mpi4py/mpi4py">mpi4py</a></b> (🥉19 ·  ⭐ 400) - Python bindings for MPI. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/mpi4py/mpi4py) (👨‍💻 16 · 🔀 65 · 📥 980 · 📋 24 - 33% open · ⏱️ 31.03.2021):

	```
	git clone https://github.com/mpi4py/mpi4py
	```
- [PyPi](https://pypi.org/project/mpi4py) (📥 220K / month):
	```
	pip install mpi4py
	```
- [Conda](https://anaconda.org/conda-forge/mpi4py) (📥 610K · ⏱️ 27.04.2021):
	```
	conda install -c conda-forge mpi4py
	```
</details>
<details><summary><b><a href="https://github.com/learning-at-home/hivemind">Hivemind</a></b> (🥉18 ·  ⭐ 680) - Decentralized deep learning in PyTorch. Built to train models on.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/learning-at-home/hivemind) (👨‍💻 16 · 🔀 40 · 📦 2 · 📋 70 - 52% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/learning-at-home/hivemind
	```
- [PyPi](https://pypi.org/project/hivemind) (📥 240 / month):
	```
	pip install hivemind
	```
</details>
<details><summary><b><a href="https://github.com/bytedance/byteps">BytePS</a></b> (🥉17 ·  ⭐ 2.8K) - A high performance and generic framework for distributed DNN training. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/bytedance/byteps) (👨‍💻 19 · 🔀 380 · 📋 230 - 36% open · ⏱️ 21.04.2021):

	```
	git clone https://github.com/bytedance/byteps
	```
- [PyPi](https://pypi.org/project/byteps) (📥 200 / month):
	```
	pip install byteps
	```
- [Docker Hub](https://hub.docker.com/r/bytepsimage/tensorflow) (📥 1.1K · ⏱️ 03.03.2020):
	```
	docker pull bytepsimage/tensorflow
	```
</details>
<details><summary><b><a href="https://github.com/uber/fiber">Fiber</a></b> (🥉17 ·  ⭐ 880) - Distributed Computing for AI Made Simple. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/uber/fiber) (👨‍💻 5 · 🔀 95 · 📦 26 · 📋 21 - 61% open · ⏱️ 15.03.2021):

	```
	git clone https://github.com/uber/fiber
	```
- [PyPi](https://pypi.org/project/fiber) (📥 1.7K / month):
	```
	pip install fiber
	```
</details>
<details><summary><b><a href="https://github.com/Ibotta/sk-dist">sk-dist</a></b> (🥉17 ·  ⭐ 260) - Distributed scikit-learn meta-estimators in PySpark. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/Ibotta/sk-dist) (👨‍💻 6 · 🔀 44 · 📦 6 · 📋 16 - 43% open · ⏱️ 01.03.2021):

	```
	git clone https://github.com/Ibotta/sk-dist
	```
- [PyPi](https://pypi.org/project/sk-dist) (📥 11K / month):
	```
	pip install sk-dist
	```
</details>
<details><summary><b><a href="https://github.com/peterwittek/somoclu">somoclu</a></b> (🥉17 ·  ⭐ 230 · 💤) - Massively parallel self-organizing maps: accelerate training on.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/peterwittek/somoclu) (👨‍💻 17 · 🔀 56 · 📥 1.5K · 📋 130 - 20% open · ⏱️ 24.07.2020):

	```
	git clone https://github.com/peterwittek/somoclu
	```
- [PyPi](https://pypi.org/project/somoclu) (📥 1.2K / month):
	```
	pip install somoclu
	```
- [Conda](https://anaconda.org/conda-forge/somoclu) (📥 46K · ⏱️ 13.10.2020):
	```
	conda install -c conda-forge somoclu
	```
</details>
<details><summary><b><a href="https://github.com/ml-tooling/lazycluster">LazyCluster</a></b> (🥉14 ·  ⭐ 37) - Distributed machine learning made simple. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/ml-tooling/lazycluster) (👨‍💻 2 · 🔀 6 · 📦 3 · ⏱️ 14.12.2020):

	```
	git clone https://github.com/ml-tooling/lazycluster
	```
- [PyPi](https://pypi.org/project/lazycluster) (📥 240 / month):
	```
	pip install lazycluster
	```
</details>
<br>

## Hyperparameter Optimization & AutoML

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for hyperparameter optimization, automl and neural architecture search._

<details><summary><b><a href="https://github.com/optuna/optuna">Optuna</a></b> (🥇32 ·  ⭐ 4.5K · 📈) - A hyperparameter optimization framework. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/optuna/optuna) (👨‍💻 130 · 🔀 500 · 📦 1.2K · 📋 760 - 19% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/optuna/optuna
	```
- [PyPi](https://pypi.org/project/optuna) (📥 460K / month):
	```
	pip install optuna
	```
- [Conda](https://anaconda.org/conda-forge/optuna) (📥 24K · ⏱️ 05.04.2021):
	```
	conda install -c conda-forge optuna
	```
</details>
<details><summary><b><a href="https://github.com/scikit-optimize/scikit-optimize">scikit-optimize</a></b> (🥇30 ·  ⭐ 2.1K) - Sequential model-based optimization with a `scipy.optimize`.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/scikit-optimize/scikit-optimize) (👨‍💻 70 · 🔀 380 · 📦 1.6K · 📋 540 - 32% open · ⏱️ 14.04.2021):

	```
	git clone https://github.com/scikit-optimize/scikit-optimize
	```
- [PyPi](https://pypi.org/project/scikit-optimize) (📥 1.4M / month):
	```
	pip install scikit-optimize
	```
- [Conda](https://anaconda.org/conda-forge/scikit-optimize) (📥 280K · ⏱️ 04.09.2020):
	```
	conda install -c conda-forge scikit-optimize
	```
</details>
<details><summary><b><a href="https://github.com/EpistasisLab/tpot">TPOT</a></b> (🥇29 ·  ⭐ 8K) - A Python Automated Machine Learning tool that optimizes machine.. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/EpistasisLab/tpot) (👨‍💻 110 · 🔀 1.4K · 📦 940 · 📋 800 - 26% open · ⏱️ 06.01.2021):

	```
	git clone https://github.com/EpistasisLab/tpot
	```
- [PyPi](https://pypi.org/project/tpot) (📥 36K / month):
	```
	pip install tpot
	```
- [Conda](https://anaconda.org/conda-forge/tpot) (📥 120K · ⏱️ 05.03.2021):
	```
	conda install -c conda-forge tpot
	```
</details>
<details><summary><b><a href="https://github.com/keras-team/autokeras">AutoKeras</a></b> (🥇28 ·  ⭐ 7.9K) - AutoML library for deep learning. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/keras-team/autokeras) (👨‍💻 130 · 🔀 1.2K · 📦 170 · 📋 730 - 8% open · ⏱️ 18.03.2021):

	```
	git clone https://github.com/keras-team/autokeras
	```
- [PyPi](https://pypi.org/project/autokeras) (📥 10K / month):
	```
	pip install autokeras
	```
</details>
<details><summary><b><a href="https://github.com/keras-team/keras-tuner">Keras Tuner</a></b> (🥇28 ·  ⭐ 2.3K) - Hyperparameter tuning for humans. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/keras-team/keras-tuner) (👨‍💻 35 · 🔀 270 · 📦 540 · 📋 300 - 48% open · ⏱️ 06.04.2021):

	```
	git clone https://github.com/keras-team/keras-tuner
	```
- [PyPi](https://pypi.org/project/keras-tuner) (📥 380K / month):
	```
	pip install keras-tuner
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/nni">NNI</a></b> (🥈27 ·  ⭐ 9.5K) - An open source AutoML toolkit for automate machine learning lifecycle,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/nni) (👨‍💻 130 · 🔀 1.3K · 📦 110 · 📋 1.2K - 20% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/microsoft/nni
	```
- [PyPi](https://pypi.org/project/nni) (📥 3.4K / month):
	```
	pip install nni
	```
</details>
<details><summary><b><a href="https://github.com/hyperopt/hyperopt">Hyperopt</a></b> (🥈27 ·  ⭐ 5.6K) - Distributed Asynchronous Hyperparameter Optimization in Python. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/hyperopt/hyperopt) (👨‍💻 87 · 🔀 760 · 📦 3.1K · 📋 560 - 60% open · ⏱️ 24.03.2021):

	```
	git clone https://github.com/hyperopt/hyperopt
	```
- [PyPi](https://pypi.org/project/hyperopt) (📥 910K / month):
	```
	pip install hyperopt
	```
- [Conda](https://anaconda.org/conda-forge/hyperopt) (📥 200K · ⏱️ 14.10.2020):
	```
	conda install -c conda-forge hyperopt
	```
</details>
<details><summary><b><a href="https://github.com/fmfn/BayesianOptimization">Bayesian Optimization</a></b> (🥈27 ·  ⭐ 5.1K) - A Python implementation of global optimization with.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/fmfn/BayesianOptimization) (👨‍💻 27 · 🔀 1.1K · 📥 54 · 📦 710 · 📋 200 - 18% open · ⏱️ 19.12.2020):

	```
	git clone https://github.com/fmfn/BayesianOptimization
	```
- [PyPi](https://pypi.org/project/bayesian-optimization) (📥 100K / month):
	```
	pip install bayesian-optimization
	```
</details>
<details><summary><b><a href="https://github.com/facebook/Ax">Ax</a></b> (🥈27 ·  ⭐ 1.5K) - Adaptive Experimentation Platform. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebook/Ax) (👨‍💻 96 · 🔀 150 · 📦 160 · 📋 240 - 4% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/facebook/Ax
	```
- [PyPi](https://pypi.org/project/ax-platform) (📥 43K / month):
	```
	pip install ax-platform
	```
</details>
<details><summary><b><a href="https://github.com/alteryx/featuretools">featuretools</a></b> (🥈26 ·  ⭐ 5.5K) - An open source python library for automated feature engineering. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/alteryx/featuretools) (👨‍💻 49 · 🔀 700 · 📦 720 · 📋 540 - 20% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/alteryx/featuretools
	```
- [PyPi](https://pypi.org/project/featuretools) (📥 220K / month):
	```
	pip install featuretools
	```
- [Conda](https://anaconda.org/conda-forge/featuretools) (📥 51K · ⏱️ 07.04.2021):
	```
	conda install -c conda-forge featuretools
	```
</details>
<details><summary><b><a href="https://github.com/awslabs/autogluon">AutoGluon</a></b> (🥈26 ·  ⭐ 3.1K) - AutoGluon: AutoML for Text, Image, and Tabular Data. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/awslabs/autogluon) (👨‍💻 56 · 🔀 400 · 📦 49 · 📋 430 - 26% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/awslabs/autogluon
	```
- [PyPi](https://pypi.org/project/autogluon) (📥 30K / month):
	```
	pip install autogluon
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/botorch">BoTorch</a></b> (🥈26 ·  ⭐ 1.9K) - Bayesian optimization in PyTorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/botorch) (👨‍💻 53 · 🔀 200 · 📦 110 · 📋 170 - 20% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/pytorch/botorch
	```
- [PyPi](https://pypi.org/project/botorch) (📥 57K / month):
	```
	pip install botorch
	```
</details>
<details><summary><b><a href="https://github.com/automl/auto-sklearn">auto-sklearn</a></b> (🥈25 ·  ⭐ 5.4K) - Automated Machine Learning with scikit-learn. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/automl/auto-sklearn) (👨‍💻 66 · 🔀 990 · 📦 160 · 📋 710 - 14% open · ⏱️ 17.04.2021):

	```
	git clone https://github.com/automl/auto-sklearn
	```
- [PyPi](https://pypi.org/project/auto-sklearn) (📥 23K / month):
	```
	pip install auto-sklearn
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/nevergrad">nevergrad</a></b> (🥈24 ·  ⭐ 2.9K) - A Python toolbox for performing gradient-free optimization. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebookresearch/nevergrad) (👨‍💻 42 · 🔀 280 · 📦 160 · 📋 180 - 30% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/facebookresearch/nevergrad
	```
- [PyPi](https://pypi.org/project/nevergrad) (📥 28K / month):
	```
	pip install nevergrad
	```
- [Conda](https://anaconda.org/conda-forge/nevergrad) (📥 8K · ⏱️ 14.12.2020):
	```
	conda install -c conda-forge nevergrad
	```
</details>
<details><summary><b><a href="https://github.com/maxpumperla/hyperas">Hyperas</a></b> (🥈23 ·  ⭐ 2.1K) - Keras + Hyperopt: A very simple wrapper for convenient.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/maxpumperla/hyperas) (👨‍💻 21 · 🔀 300 · 📦 200 · 📋 250 - 35% open · ⏱️ 22.12.2020):

	```
	git clone https://github.com/maxpumperla/hyperas
	```
- [PyPi](https://pypi.org/project/hyperas) (📥 38K / month):
	```
	pip install hyperas
	```
</details>
<details><summary><b><a href="https://github.com/autonomio/talos">Talos</a></b> (🥈23 ·  ⭐ 1.4K) - Hyperparameter Optimization for TensorFlow, Keras and PyTorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/autonomio/talos) (👨‍💻 19 · 🔀 230 · 📦 110 · 📋 380 - 8% open · ⏱️ 21.11.2020):

	```
	git clone https://github.com/autonomio/talos
	```
- [PyPi](https://pypi.org/project/talos) (📥 2.3K / month):
	```
	pip install talos
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/adanet">AdaNet</a></b> (🥈22 ·  ⭐ 3.3K · 💤) - Fast and flexible AutoML with learning guarantees. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/adanet) (👨‍💻 26 · 🔀 510 · 📦 36 · 📋 110 - 58% open · ⏱️ 09.07.2020):

	```
	git clone https://github.com/tensorflow/adanet
	```
- [PyPi](https://pypi.org/project/adanet) (📥 1.2K / month):
	```
	pip install adanet
	```
</details>
<details><summary><b><a href="https://github.com/mljar/mljar-supervised">mljar-supervised</a></b> (🥈22 ·  ⭐ 1.1K) - Automated Machine Learning Pipeline with Feature Engineering.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mljar/mljar-supervised) (👨‍💻 9 · 🔀 130 · 📦 10 · 📋 360 - 10% open · ⏱️ 17.04.2021):

	```
	git clone https://github.com/mljar/mljar-supervised
	```
- [PyPi](https://pypi.org/project/mljar-supervised) (📥 3.7K / month):
	```
	pip install mljar-supervised
	```
</details>
<details><summary><b><a href="https://github.com/SheffieldML/GPyOpt">GPyOpt</a></b> (🥈22 ·  ⭐ 730) - Gaussian Process Optimization using GPy. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/SheffieldML/GPyOpt) (👨‍💻 49 · 🔀 220 · 📦 190 · 📋 280 - 34% open · ⏱️ 05.11.2020):

	```
	git clone https://github.com/SheffieldML/GPyOpt
	```
- [PyPi](https://pypi.org/project/gpyopt) (📥 12K / month):
	```
	pip install gpyopt
	```
</details>
<details><summary><b><a href="https://github.com/ClimbsRocks/auto_ml">auto_ml</a></b> (🥉21 ·  ⭐ 1.5K · 💀) - [UNMAINTAINED] Automated machine learning for analytics & production. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ClimbsRocks/auto_ml) (👨‍💻 13 · 🔀 300 · 📥 33 · 📋 390 - 45% open · ⏱️ 25.03.2018):

	```
	git clone https://github.com/ClimbsRocks/auto_ml
	```
- [PyPi](https://pypi.org/project/auto_ml) (📥 4.4K / month):
	```
	pip install auto_ml
	```
</details>
<details><summary><b><a href="https://github.com/automl/SMAC3">SMAC3</a></b> (🥉21 ·  ⭐ 570) - Sequential Model-based Algorithm Configuration. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/automl/SMAC3) (👨‍💻 30 · 🔀 160 · 📋 320 - 22% open · ⏱️ 29.10.2020):

	```
	git clone https://github.com/automl/SMAC3
	```
- [PyPi](https://pypi.org/project/smac) (📥 35K / month):
	```
	pip install smac
	```
</details>
<details><summary><b><a href="https://github.com/Neuraxio/Neuraxle">Neuraxle</a></b> (🥉21 ·  ⭐ 400) - A Sklearn-like Framework for Hyperparameter Tuning and AutoML in.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Neuraxio/Neuraxle) (👨‍💻 7 · 🔀 41 · 📦 18 · 📋 280 - 47% open · ⏱️ 30.03.2021):

	```
	git clone https://github.com/Neuraxio/Neuraxle
	```
- [PyPi](https://pypi.org/project/neuraxle) (📥 460 / month):
	```
	pip install neuraxle
	```
</details>
<details><summary><b><a href="https://github.com/claesenm/optunity">optunity</a></b> (🥉21 ·  ⭐ 370 · 💤) - optimization routines for hyperparameter tuning. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/claesenm/optunity) (👨‍💻 9 · 🔀 73 · 📥 64 · 📦 60 · 📋 94 - 48% open · ⏱️ 11.05.2020):

	```
	git clone https://github.com/claesenm/optunity
	```
- [PyPi](https://pypi.org/project/optunity) (📥 16K / month):
	```
	pip install optunity
	```
</details>
<details><summary><b><a href="https://github.com/AxeldeRomblay/MLBox">MLBox</a></b> (🥉20 ·  ⭐ 1.2K · 💤) - MLBox is a powerful Automated Machine Learning python library. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/AxeldeRomblay/MLBox) (👨‍💻 9 · 🔀 250 · 📦 23 · 📋 86 - 15% open · ⏱️ 25.08.2020):

	```
	git clone https://github.com/AxeldeRomblay/MLBox
	```
- [PyPi](https://pypi.org/project/mlbox) (📥 3K / month):
	```
	pip install mlbox
	```
</details>
<details><summary><b><a href="https://github.com/automl/HpBandSter">HpBandSter</a></b> (🥉19 ·  ⭐ 460 · 💀) - a distributed Hyperband implementation on Steroids. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/automl/HpBandSter) (👨‍💻 11 · 🔀 98 · 📦 140 · 📋 84 - 58% open · ⏱️ 26.03.2019):

	```
	git clone https://github.com/automl/HpBandSter
	```
- [PyPi](https://pypi.org/project/hpbandster) (📥 20K / month):
	```
	pip install hpbandster
	```
</details>
<details><summary><b><a href="https://github.com/shankarpandala/lazypredict">lazypredict</a></b> (🥉19 ·  ⭐ 450) - Lazy Predict help build a lot of basic models without much code.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/shankarpandala/lazypredict) (👨‍💻 12 · 🔀 93 · 📦 55 · 📋 47 - 36% open · ⏱️ 10.04.2021):

	```
	git clone https://github.com/shankarpandala/lazypredict
	```
- [PyPi](https://pypi.org/project/lazypredict) (📥 3.9K / month):
	```
	pip install lazypredict
	```
</details>
<details><summary><b><a href="https://github.com/Epistimio/orion">Orion</a></b> (🥉19 ·  ⭐ 190) - Asynchronous Distributed Hyperparameter Optimization. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/Epistimio/orion) (👨‍💻 23 · 🔀 38 · 📦 40 · 📋 150 - 25% open · ⏱️ 24.04.2021):

	```
	git clone https://github.com/Epistimio/orion
	```
- [PyPi](https://pypi.org/project/orion) (📥 3.2K / month):
	```
	pip install orion
	```
</details>
<details><summary><b><a href="https://github.com/AutoViML/Auto_ViML">Auto ViML</a></b> (🥉18 ·  ⭐ 240) - Automatically Build Multiple ML Models with a Single Line of Code... <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/AutoViML/Auto_ViML) (👨‍💻 6 · 🔀 53 · 📦 13 · 📋 18 - 22% open · ⏱️ 14.04.2021):

	```
	git clone https://github.com/AutoViML/Auto_ViML
	```
- [PyPi](https://pypi.org/project/autoviml) (📥 3.2K / month):
	```
	pip install autoviml
	```
</details>
<details><summary><b><a href="https://github.com/williamFalcon/test-tube">Test Tube</a></b> (🥉17 ·  ⭐ 680 · 💀) - Python library to easily log experiments and parallelize.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/williamFalcon/test-tube) (👨‍💻 16 · 🔀 60 · 📥 8 · 📋 44 - 52% open · ⏱️ 17.03.2020):

	```
	git clone https://github.com/williamFalcon/test-tube
	```
- [PyPi](https://pypi.org/project/test_tube) (📥 16K / month):
	```
	pip install test_tube
	```
</details>
<details><summary><b><a href="https://github.com/rsteca/sklearn-deap">sklearn-deap</a></b> (🥉17 ·  ⭐ 640 · 💀) - Use evolutionary algorithms instead of gridsearch in.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rsteca/sklearn-deap) (👨‍💻 20 · 🔀 110 · 📦 25 · 📋 47 - 34% open · ⏱️ 03.12.2019):

	```
	git clone https://github.com/rsteca/sklearn-deap
	```
- [PyPi](https://pypi.org/project/sklearn-deap) (📥 820 / month):
	```
	pip install sklearn-deap
	```
</details>
<details><summary><b><a href="https://github.com/ScottfreeLLC/AlphaPy">AlphaPy</a></b> (🥉17 ·  ⭐ 580) - Automated Machine Learning [AutoML] with Python, scikit-learn, Keras,.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/ScottfreeLLC/AlphaPy) (👨‍💻 3 · 🔀 130 · 📦 2 · 📋 38 - 23% open · ⏱️ 08.02.2021):

	```
	git clone https://github.com/ScottfreeLLC/AlphaPy
	```
- [PyPi](https://pypi.org/project/alphapy) (📥 410 / month):
	```
	pip install alphapy
	```
</details>
<details><summary><b><a href="https://github.com/HDI-Project/ATM">Auto Tune Models</a></b> (🥉17 ·  ⭐ 510 · 💀) - Auto Tune Models - A multi-tenant, multi-data system for.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/HDI-Project/ATM) (👨‍💻 16 · 🔀 130 · 📦 6 · 📋 88 - 19% open · ⏱️ 21.02.2020):

	```
	git clone https://github.com/HDI-Project/ATM
	```
- [PyPi](https://pypi.org/project/atm) (📥 200 / month):
	```
	pip install atm
	```
</details>
<details><summary><b><a href="https://github.com/sherpa-ai/sherpa">Sherpa</a></b> (🥉17 ·  ⭐ 290) - Hyperparameter optimization that enables researchers to.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/sherpa-ai/sherpa) (👨‍💻 43 · 🔀 44 · 📦 10 · 📋 53 - 22% open · ⏱️ 18.10.2020):

	```
	git clone https://github.com/sherpa-ai/sherpa
	```
- [PyPi](https://pypi.org/project/parameter-sherpa) (📥 380 / month):
	```
	pip install parameter-sherpa
	```
</details>
<details><summary><b><a href="https://github.com/minimaxir/automl-gs">automl-gs</a></b> (🥉16 ·  ⭐ 1.7K · 💀) - Provide an input CSV and a target field to predict, generate a.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/minimaxir/automl-gs) (👨‍💻 7 · 🔀 150 · 📥 21 · 📋 29 - 79% open · ⏱️ 05.04.2019):

	```
	git clone https://github.com/minimaxir/automl-gs
	```
- [PyPi](https://pypi.org/project/automl_gs) (📥 50 / month):
	```
	pip install automl_gs
	```
</details>
<details><summary><b><a href="https://github.com/reiinakano/xcessiv">Xcessiv</a></b> (🥉16 ·  ⭐ 1.3K · 💀) - A web-based application for quick, scalable, and automated.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/reiinakano/xcessiv) (👨‍💻 6 · 🔀 100 · 📦 1 · 📋 34 - 61% open · ⏱️ 21.08.2017):

	```
	git clone https://github.com/reiinakano/xcessiv
	```
- [PyPi](https://pypi.org/project/xcessiv) (📥 120 / month):
	```
	pip install xcessiv
	```
</details>
<details><summary><b><a href="https://github.com/HunterMcGushion/hyperparameter_hunter">HyperparameterHunter</a></b> (🥉16 ·  ⭐ 650) - Easy hyperparameter optimization and automatic result.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/HunterMcGushion/hyperparameter_hunter) (👨‍💻 4 · 🔀 83 · 📥 270 · 📋 120 - 27% open · ⏱️ 20.01.2021):

	```
	git clone https://github.com/HunterMcGushion/hyperparameter_hunter
	```
- [PyPi](https://pypi.org/project/hyperparameter-hunter) (📥 260 / month):
	```
	pip install hyperparameter-hunter
	```
</details>
<details><summary><b><a href="https://github.com/dragonfly/dragonfly">Dragonfly</a></b> (🥉16 ·  ⭐ 580 · 💤) - An open source python library for scalable Bayesian optimisation. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/dragonfly/dragonfly) (👨‍💻 12 · 🔀 77 · 📋 42 - 59% open · ⏱️ 03.07.2020):

	```
	git clone https://github.com/dragonfly/dragonfly
	```
- [PyPi](https://pypi.org/project/dragonfly-opt) (📥 20K / month):
	```
	pip install dragonfly-opt
	```
</details>
<details><summary><b><a href="https://github.com/tobegit3hub/advisor">Advisor</a></b> (🥉15 ·  ⭐ 1.4K · 💀) - Open-source implementation of Google Vizier for hyper parameters.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/tobegit3hub/advisor) (👨‍💻 11 · 🔀 240 · 📋 32 - 59% open · ⏱️ 11.11.2019):

	```
	git clone https://github.com/tobegit3hub/advisor
	```
- [PyPi](https://pypi.org/project/advisor) (📥 80 / month):
	```
	pip install advisor
	```
- [Docker Hub](https://hub.docker.com/r/tobegit3hub/advisor) (📥 1.6K · ⏱️ 11.11.2019):
	```
	docker pull tobegit3hub/advisor
	```
</details>
<details><summary><b><a href="https://github.com/jmcarpenter2/parfit">Parfit</a></b> (🥉15 ·  ⭐ 200 · 💤) - A package for parallelizing the fit and flexibly scoring of.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/jmcarpenter2/parfit) (👨‍💻 2 · 🔀 25 · 📦 8 · 📋 11 - 54% open · ⏱️ 04.04.2020):

	```
	git clone https://github.com/jmcarpenter2/parfit
	```
- [PyPi](https://pypi.org/project/parfit) (📥 12K / month):
	```
	pip install parfit
	```
</details>
<details><summary><b><a href="https://github.com/LGE-ARC-AdvancedAI/auptimizer">Auptimizer</a></b> (🥉14 ·  ⭐ 170) - An automatic ML model optimization tool. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/LGE-ARC-AdvancedAI/auptimizer) (👨‍💻 11 · 🔀 18 · ⏱️ 03.03.2021):

	```
	git clone https://github.com/LGE-ARC-AdvancedAI/auptimizer
	```
- [PyPi](https://pypi.org/project/auptimizer) (📥 240 / month):
	```
	pip install auptimizer
	```
</details>
<details><summary><b><a href="https://github.com/carpedm20/ENAS-pytorch">ENAS</a></b> (🥉13 ·  ⭐ 2.4K · 💤) - PyTorch implementation of Efficient Neural Architecture Search via.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/carpedm20/ENAS-pytorch) (👨‍💻 6 · 🔀 450 · 📋 44 - 84% open · ⏱️ 16.06.2020):

	```
	git clone https://github.com/carpedm20/ENAS-pytorch
	```
</details>
<details><summary><b><a href="https://github.com/electricbrainio/hypermax">Hypermax</a></b> (🥉12 ·  ⭐ 96 · 💤) - Better, faster hyper-parameter optimization. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/electricbrainio/hypermax) (👨‍💻 9 · 🔀 15 · 📦 4 · 📋 4 - 75% open · ⏱️ 02.08.2020):

	```
	git clone https://github.com/electricbrainio/hypermax
	```
- [PyPi](https://pypi.org/project/hypermax) (📥 100 / month):
	```
	pip install hypermax
	```
</details>
<details><summary><b><a href="https://github.com/joeddav/devol">Devol</a></b> (🥉11 ·  ⭐ 930 · 💤) - Genetic neural architecture search with Keras. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/joeddav/devol) (👨‍💻 18 · 🔀 110 · 📋 27 - 25% open · ⏱️ 05.07.2020):

	```
	git clone https://github.com/joeddav/devol
	```
</details>
<details><summary><b><a href="https://github.com/gdikov/hypertunity">Hypertunity</a></b> (🥉11 ·  ⭐ 120 · 💀) - A toolset for black-box hyperparameter optimisation. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/gdikov/hypertunity) (👨‍💻 2 · 🔀 9 · 📦 2 · ⏱️ 26.01.2020):

	```
	git clone https://github.com/gdikov/hypertunity
	```
- [PyPi](https://pypi.org/project/hypertunity) (📥 52 / month):
	```
	pip install hypertunity
	```
</details>
<details><summary><b><a href="https://github.com/AutoViML/featurewiz">featurewiz</a></b> (🥉10 ·  ⭐ 51 · 🐣) - Use advanced feature engineering strategies and select the.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/AutoViML/featurewiz) (🔀 15 · ⏱️ 26.04.2021):

	```
	git clone https://github.com/AutoViML/featurewiz
	```
- [PyPi](https://pypi.org/project/featurewiz) (📥 1K / month):
	```
	pip install featurewiz
	```
</details>
<br>

## Reinforcement Learning

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for building and evaluating reinforcement learning & agent-based systems._

<details><summary><b><a href="https://github.com/openai/gym">OpenAI Gym</a></b> (🥇35 ·  ⭐ 24K · 📈) - A toolkit for developing and comparing reinforcement learning.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/openai/gym) (👨‍💻 280 · 🔀 6.4K · 📦 20K · 📋 1.3K - 18% open · ⏱️ 06.04.2021):

	```
	git clone https://github.com/openai/gym
	```
- [PyPi](https://pypi.org/project/gym) (📥 450K / month):
	```
	pip install gym
	```
</details>
<details><summary><b><a href="https://github.com/openai/baselines">baselines</a></b> (🥇26 ·  ⭐ 11K · 💀) - OpenAI Baselines: high-quality implementations of reinforcement.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/openai/baselines) (👨‍💻 110 · 🔀 3.2K · 📦 300 · 📋 810 - 47% open · ⏱️ 31.01.2020):

	```
	git clone https://github.com/openai/baselines
	```
- [PyPi](https://pypi.org/project/baselines) (📥 11K / month):
	```
	pip install baselines
	```
</details>
<details><summary><b><a href="https://github.com/keras-rl/keras-rl">keras-rl</a></b> (🥈25 ·  ⭐ 5K · 💀) - Deep Reinforcement Learning for Keras. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/keras-rl/keras-rl) (👨‍💻 40 · 🔀 1.3K · 📦 480 · 📋 220 - 4% open · ⏱️ 11.11.2019):

	```
	git clone https://github.com/keras-rl/keras-rl
	```
- [PyPi](https://pypi.org/project/keras-rl) (📥 2.9K / month):
	```
	pip install keras-rl
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/agents">TF-Agents</a></b> (🥈25 ·  ⭐ 1.9K) - TF-Agents: A reliable, scalable and easy to use TensorFlow.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/agents) (👨‍💻 92 · 🔀 470 · 📦 440 · 📋 440 - 21% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/tensorflow/agents
	```
- [PyPi](https://pypi.org/project/tf-agents) (📥 16K / month):
	```
	pip install tf-agents
	```
</details>
<details><summary><b><a href="https://github.com/google/dopamine">Dopamine</a></b> (🥈23 ·  ⭐ 9.4K) - Dopamine is a research framework for fast prototyping of.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/google/dopamine) (👨‍💻 14 · 🔀 1.2K · 📋 130 - 45% open · ⏱️ 08.04.2021):

	```
	git clone https://github.com/google/dopamine
	```
- [PyPi](https://pypi.org/project/dopamine-rl) (📥 110K / month):
	```
	pip install dopamine-rl
	```
</details>
<details><summary><b><a href="https://github.com/tensorforce/tensorforce">TensorForce</a></b> (🥈23 ·  ⭐ 2.9K) - Tensorforce: a TensorFlow library for applied.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorforce/tensorforce) (👨‍💻 76 · 🔀 480 · 📋 560 - 1% open · ⏱️ 20.04.2021):

	```
	git clone https://github.com/tensorforce/tensorforce
	```
- [PyPi](https://pypi.org/project/tensorforce) (📥 1.8K / month):
	```
	pip install tensorforce
	```
</details>
<details><summary><b><a href="https://github.com/deepmind/acme">Acme</a></b> (🥈23 ·  ⭐ 2K) - A library of reinforcement learning components and agents. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deepmind/acme) (👨‍💻 38 · 🔀 210 · 📦 26 · 📋 92 - 45% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/deepmind/acme
	```
- [PyPi](https://pypi.org/project/dm-acme) (📥 2K / month):
	```
	pip install dm-acme
	```
</details>
<details><summary><b><a href="https://github.com/mwydmuch/ViZDoom">ViZDoom</a></b> (🥈23 ·  ⭐ 1.2K) - Doom-based AI Research Platform for Reinforcement Learning from.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/mwydmuch/ViZDoom) (👨‍💻 44 · 🔀 290 · 📥 11K · 📦 110 · 📋 420 - 20% open · ⏱️ 09.02.2021):

	```
	git clone https://github.com/mwydmuch/ViZDoom
	```
- [PyPi](https://pypi.org/project/vizdoom) (📥 1.6K / month):
	```
	pip install vizdoom
	```
</details>
<details><summary><b><a href="https://github.com/chainer/chainerrl">ChainerRL</a></b> (🥈23 ·  ⭐ 940) - ChainerRL is a deep reinforcement learning library built on top of.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/chainer/chainerrl) (👨‍💻 29 · 🔀 200 · 📦 97 · 📋 200 - 25% open · ⏱️ 17.04.2021):

	```
	git clone https://github.com/chainer/chainerrl
	```
- [PyPi](https://pypi.org/project/chainerrl) (📥 670 / month):
	```
	pip install chainerrl
	```
</details>
<details><summary><b><a href="https://github.com/tensorlayer/tensorlayer">TensorLayer</a></b> (🥉22 ·  ⭐ 6.6K) - Deep Learning and Reinforcement Learning Library for.. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorlayer/tensorlayer) (👨‍💻 130 · 🔀 1.5K · 📥 1.3K · 📋 450 - 3% open · ⏱️ 17.03.2021):

	```
	git clone https://github.com/tensorlayer/tensorlayer
	```
- [PyPi](https://pypi.org/project/tensorlayer) (📥 3.6K / month):
	```
	pip install tensorlayer
	```
</details>
<details><summary><b><a href="https://github.com/hill-a/stable-baselines">Stable Baselines</a></b> (🥉22 ·  ⭐ 3.1K) - A fork of OpenAI Baselines, implementations of reinforcement.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/hill-a/stable-baselines) (👨‍💻 110 · 🔀 600 · 📋 870 - 13% open · ⏱️ 19.04.2021):

	```
	git clone https://github.com/hill-a/stable-baselines
	```
- [PyPi](https://pypi.org/project/stable-baselines) (📥 14K / month):
	```
	pip install stable-baselines
	```
</details>
<details><summary><b><a href="https://github.com/rlworkgroup/garage">garage</a></b> (🥉22 ·  ⭐ 1.1K) - A toolkit for reproducible reinforcement learning research. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rlworkgroup/garage) (👨‍💻 75 · 🔀 220 · 📦 17 · 📋 960 - 18% open · ⏱️ 13.04.2021):

	```
	git clone https://github.com/rlworkgroup/garage
	```
- [PyPi](https://pypi.org/project/garage) (📥 540 / month):
	```
	pip install garage
	```
</details>
<details><summary><b><a href="https://github.com/IntelLabs/coach">Coach</a></b> (🥉20 ·  ⭐ 2K) - Reinforcement Learning Coach by Intel AI Lab enables easy.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/IntelLabs/coach) (👨‍💻 34 · 🔀 380 · 📋 260 - 29% open · ⏱️ 09.02.2021):

	```
	git clone https://github.com/IntelLabs/coach
	```
- [PyPi](https://pypi.org/project/rl_coach) (📥 250 / month):
	```
	pip install rl_coach
	```
</details>
<details><summary><b><a href="https://github.com/PaddlePaddle/PARL">PARL</a></b> (🥉20 ·  ⭐ 2K) - A high-performance distributed training framework for Reinforcement.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PaddlePaddle/PARL) (👨‍💻 23 · 🔀 460 · 📦 72 · 📋 220 - 22% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/PaddlePaddle/PARL
	```
- [PyPi](https://pypi.org/project/parl) (📥 820 / month):
	```
	pip install parl
	```
</details>
<details><summary><b><a href="https://github.com/pfnet/pfrl">PFRL</a></b> (🥉20 ·  ⭐ 580) - PFRL: a PyTorch-based deep reinforcement learning library. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pfnet/pfrl) (👨‍💻 13 · 🔀 70 · 📦 8 · 📋 42 - 40% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/pfnet/pfrl
	```
- [PyPi](https://pypi.org/project/pfrl) (📥 1.2K / month):
	```
	pip install pfrl
	```
</details>
<details><summary><b><a href="https://github.com/deepmind/trfl">TRFL</a></b> (🥉19 ·  ⭐ 3.1K · 💤) - TensorFlow Reinforcement Learning. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deepmind/trfl) (👨‍💻 12 · 🔀 370 · 📦 46 · 📋 20 - 20% open · ⏱️ 20.04.2020):

	```
	git clone https://github.com/deepmind/trfl
	```
- [PyPi](https://pypi.org/project/trfl) (📥 2.2K / month):
	```
	pip install trfl
	```
</details>
<details><summary><b><a href="https://github.com/deepmind/lab">DeepMind Lab</a></b> (🥉17 ·  ⭐ 6.4K) - A customisable 3D platform for agent-based AI research. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/deepmind/lab) (👨‍💻 7 · 🔀 1.3K · 📋 190 - 18% open · ⏱️ 04.03.2021):

	```
	git clone https://github.com/deepmind/lab
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/ReAgent">ReAgent</a></b> (🥉17 ·  ⭐ 2.9K) - A platform for Reasoning systems (Reinforcement Learning,.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/ReAgent) (👨‍💻 96 · 🔀 390 · 📋 95 - 21% open · ⏱️ 23.04.2021):

	```
	git clone https://github.com/facebookresearch/ReAgent
	```
</details>
<details><summary><b><a href="https://github.com/deepmind/rlax">RLax</a></b> (🥉16 ·  ⭐ 590) - A library of reinforcement learning building blocks in JAX. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code>jax</code></summary>

- [GitHub](https://github.com/deepmind/rlax) (👨‍💻 11 · 🔀 47 · 📦 16 · 📋 7 - 42% open · ⏱️ 13.04.2021):

	```
	git clone https://github.com/deepmind/rlax
	```
- [PyPi](https://pypi.org/project/rlax) (📥 390 / month):
	```
	pip install rlax
	```
</details>
<br>

## Recommender Systems

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for building and evaluating recommendation systems._

<details><summary><b><a href="https://github.com/lyst/lightfm">lightfm</a></b> (🥇27 ·  ⭐ 3.6K) - A Python implementation of LightFM, a hybrid recommendation algorithm. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/lyst/lightfm) (👨‍💻 44 · 🔀 580 · 📦 440 · 📋 410 - 17% open · ⏱️ 07.02.2021):

	```
	git clone https://github.com/lyst/lightfm
	```
- [PyPi](https://pypi.org/project/lightfm) (📥 160K / month):
	```
	pip install lightfm
	```
- [Conda](https://anaconda.org/conda-forge/lightfm) (📥 88K · ⏱️ 07.02.2021):
	```
	conda install -c conda-forge lightfm
	```
</details>
<details><summary><b><a href="https://github.com/benfred/implicit">implicit</a></b> (🥇26 ·  ⭐ 2.3K) - Fast Python Collaborative Filtering for Implicit Feedback Datasets. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/benfred/implicit) (👨‍💻 29 · 🔀 460 · 📦 400 · 📋 340 - 23% open · ⏱️ 25.04.2021):

	```
	git clone https://github.com/benfred/implicit
	```
- [PyPi](https://pypi.org/project/implicit) (📥 61K / month):
	```
	pip install implicit
	```
- [Conda](https://anaconda.org/conda-forge/implicit) (📥 230K · ⏱️ 24.11.2020):
	```
	conda install -c conda-forge implicit
	```
</details>
<details><summary><b><a href="https://github.com/NicolasHug/Surprise">scikit-surprise</a></b> (🥈25 ·  ⭐ 4.8K · 💤) - A Python scikit for building and analyzing recommender.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/NicolasHug/Surprise) (👨‍💻 38 · 🔀 850 · 📦 1K · 📋 330 - 11% open · ⏱️ 05.08.2020):

	```
	git clone https://github.com/NicolasHug/Surprise
	```
- [PyPi](https://pypi.org/project/scikit-surprise) (📥 49K / month):
	```
	pip install scikit-surprise
	```
- [Conda](https://anaconda.org/conda-forge/scikit-surprise) (📥 170K · ⏱️ 13.10.2020):
	```
	conda install -c conda-forge scikit-surprise
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/ranking">TF Ranking</a></b> (🥈23 ·  ⭐ 2.1K) - Learning to Rank in TensorFlow. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/ranking) (👨‍💻 20 · 🔀 370 · 📋 230 - 10% open · ⏱️ 04.02.2021):

	```
	git clone https://github.com/tensorflow/ranking
	```
- [PyPi](https://pypi.org/project/tensorflow_ranking) (📥 80K / month):
	```
	pip install tensorflow_ranking
	```
</details>
<details><summary><b><a href="https://github.com/PreferredAI/cornac">Cornac</a></b> (🥈23 ·  ⭐ 320) - A Comparative Framework for Multimodal Recommender Systems. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/PreferredAI/cornac) (👨‍💻 11 · 🔀 63 · 📦 40 · ⏱️ 24.04.2021):

	```
	git clone https://github.com/PreferredAI/cornac
	```
- [PyPi](https://pypi.org/project/cornac) (📥 3.7K / month):
	```
	pip install cornac
	```
- [Conda](https://anaconda.org/conda-forge/cornac) (📥 130K · ⏱️ 30.03.2021):
	```
	conda install -c conda-forge cornac
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/recommenders">Recommenders</a></b> (🥉21 ·  ⭐ 9.6K) - Best Practices on Recommendation Systems. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/recommenders) (👨‍💻 93 · 🔀 1.6K · 📦 2 · 📋 570 - 21% open · ⏱️ 06.04.2021):

	```
	git clone https://github.com/microsoft/recommenders
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/recommenders">TF Recommenders</a></b> (🥉21 ·  ⭐ 800) - TensorFlow Recommenders is a library for building.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/recommenders) (👨‍💻 21 · 🔀 94 · 📦 19 · 📋 120 - 46% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/tensorflow/recommenders
	```
- [PyPi](https://pypi.org/project/tensorflow-recommenders) (📥 24K / month):
	```
	pip install tensorflow-recommenders
	```
</details>
<details><summary><b><a href="https://github.com/RUCAIBox/RecBole">RecBole</a></b> (🥉20 ·  ⭐ 910) - A unified, comprehensive and efficient recommendation library. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/RUCAIBox/RecBole) (👨‍💻 38 · 🔀 140 · 📋 110 - 21% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/RUCAIBox/RecBole
	```
- [PyPi](https://pypi.org/project/recbole) (📥 680 / month):
	```
	pip install recbole
	```
- [Conda](https://anaconda.org/aibox/recbole) (📥 340 · ⏱️ 22.03.2021):
	```
	conda install -c aibox recbole
	```
</details>
<details><summary><b><a href="https://github.com/jfkirk/tensorrec">tensorrec</a></b> (🥉19 ·  ⭐ 1.1K · 💀) - A TensorFlow recommendation algorithm and framework in.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/jfkirk/tensorrec) (👨‍💻 8 · 🔀 210 · 📦 25 · 📋 120 - 26% open · ⏱️ 04.02.2020):

	```
	git clone https://github.com/jfkirk/tensorrec
	```
- [PyPi](https://pypi.org/project/tensorrec) (📥 1K / month):
	```
	pip install tensorrec
	```
</details>
<details><summary><b><a href="https://github.com/ibayer/fastFM">fastFM</a></b> (🥉19 ·  ⭐ 920) - fastFM: A Library for Factorization Machines. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/ibayer/fastFM) (👨‍💻 20 · 🔀 190 · 📥 390 · 📦 80 · 📋 100 - 42% open · ⏱️ 24.03.2021):

	```
	git clone https://github.com/ibayer/fastFM
	```
- [PyPi](https://pypi.org/project/fastfm) (📥 1K / month):
	```
	pip install fastfm
	```
</details>
<details><summary><b><a href="https://github.com/maciejkula/spotlight">Spotlight</a></b> (🥉17 ·  ⭐ 2.5K · 💀) - Deep recommender models using PyTorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/maciejkula/spotlight) (👨‍💻 11 · 🔀 370 · 📋 110 - 55% open · ⏱️ 09.02.2020):

	```
	git clone https://github.com/maciejkula/spotlight
	```
- [Conda](https://anaconda.org/maciejkula/spotlight) (📥 6.2K · ⏱️ 27.05.2018):
	```
	conda install -c maciejkula spotlight
	```
</details>
<details><summary><b><a href="https://github.com/caserec/CaseRecommender">Case Recommender</a></b> (🥉16 ·  ⭐ 320 · 💤) - Case Recommender: A Flexible and Extensible Python.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/caserec/CaseRecommender) (👨‍💻 10 · 🔀 70 · 📦 9 · 📋 23 - 30% open · ⏱️ 26.05.2020):

	```
	git clone https://github.com/caserec/CaseRecommender
	```
- [PyPi](https://pypi.org/project/caserecommender) (📥 540 / month):
	```
	pip install caserecommender
	```
</details>
<details><summary><b><a href="https://github.com/statisticianinstilettos/recmetrics">recmetrics</a></b> (🥉16 ·  ⭐ 260) - A library of metrics for evaluating recommender systems. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/statisticianinstilettos/recmetrics) (👨‍💻 12 · 🔀 62 · 📦 17 · 📋 10 - 30% open · ⏱️ 03.12.2020):

	```
	git clone https://github.com/statisticianinstilettos/recmetrics
	```
- [PyPi](https://pypi.org/project/recmetrics) (📥 390 / month):
	```
	pip install recmetrics
	```
</details>
<br>

## Privacy Machine Learning

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for encrypted and privacy-preserving machine learning using methods like federated learning & differential privacy._

<details><summary><b><a href="https://github.com/OpenMined/PySyft">PySyft</a></b> (🥇25 ·  ⭐ 7.1K) - A library for answering questions using data you cannot see. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/OpenMined/PySyft) (👨‍💻 370 · 🔀 1.6K · 📋 2.9K - 5% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/OpenMined/PySyft
	```
- [PyPi](https://pypi.org/project/syft) (📥 3.6K / month):
	```
	pip install syft
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/opacus">Opacus</a></b> (🥈22 ·  ⭐ 800) - Training PyTorch models with differential privacy. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/opacus) (👨‍💻 29 · 🔀 120 · 📥 31 · 📦 28 · 📋 74 - 14% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/pytorch/opacus
	```
- [PyPi](https://pypi.org/project/opacus) (📥 7.6K / month):
	```
	pip install opacus
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/privacy">TensorFlow Privacy</a></b> (🥈21 ·  ⭐ 1.4K) - Library for training machine learning models with.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/privacy) (👨‍💻 36 · 🔀 280 · 📥 42 · 📋 120 - 37% open · ⏱️ 20.04.2021):

	```
	git clone https://github.com/tensorflow/privacy
	```
- [PyPi](https://pypi.org/project/tensorflow-privacy) (📥 12K / month):
	```
	pip install tensorflow-privacy
	```
</details>
<details><summary><b><a href="https://github.com/FederatedAI/FATE">FATE</a></b> (🥉20 ·  ⭐ 3K) - An Industrial Grade Federated Learning Framework. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/FederatedAI/FATE) (👨‍💻 56 · 🔀 870 · 📋 840 - 34% open · ⏱️ 16.04.2021):

	```
	git clone https://github.com/FederatedAI/FATE
	```
</details>
<details><summary><b><a href="https://github.com/tf-encrypted/tf-encrypted">TFEncrypted</a></b> (🥉19 ·  ⭐ 850 · 💤) - A Framework for Encrypted Machine Learning in TensorFlow. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tf-encrypted/tf-encrypted) (👨‍💻 28 · 🔀 140 · 📦 48 · 📋 400 - 41% open · ⏱️ 19.08.2020):

	```
	git clone https://github.com/tf-encrypted/tf-encrypted
	```
- [PyPi](https://pypi.org/project/tf-encrypted) (📥 1.1K / month):
	```
	pip install tf-encrypted
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/CrypTen">CrypTen</a></b> (🥉17 ·  ⭐ 780) - A framework for Privacy Preserving Machine Learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/CrypTen) (👨‍💻 23 · 🔀 110 · 📦 7 · 📋 55 - 25% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/facebookresearch/CrypTen
	```
- [PyPi](https://pypi.org/project/crypten) (📥 250 / month):
	```
	pip install crypten
	```
</details>
<br>

## Workflow & Experiment Tracking

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries to organize, track, and visualize machine learning experiments._

<details><summary><b><a href="https://github.com/tensorflow/tensorboard">Tensorboard</a></b> (🥇36 ·  ⭐ 5.3K) - TensorFlow's Visualization Toolkit. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/tensorboard) (👨‍💻 260 · 🔀 1.3K · 📦 62K · 📋 1.5K - 34% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/tensorflow/tensorboard
	```
- [PyPi](https://pypi.org/project/tensorboard) (📥 9.1M / month):
	```
	pip install tensorboard
	```
- [Conda](https://anaconda.org/conda-forge/tensorboard) (📥 1.9M · ⏱️ 15.01.2021):
	```
	conda install -c conda-forge tensorboard
	```
</details>
<details><summary><b><a href="https://github.com/iterative/dvc">DVC</a></b> (🥇31 ·  ⭐ 7.8K) - Data Version Control | Git for Data & Models. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/iterative/dvc) (👨‍💻 220 · 🔀 730 · 📥 23K · 📦 910 · 📋 2.9K - 18% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/iterative/dvc
	```
- [PyPi](https://pypi.org/project/dvc) (📥 160K / month):
	```
	pip install dvc
	```
- [Conda](https://anaconda.org/conda-forge/dvc) (📥 620K · ⏱️ 23.04.2021):
	```
	conda install -c conda-forge dvc
	```
</details>
<details><summary><b><a href="https://github.com/aws/sagemaker-python-sdk">SageMaker SDK</a></b> (🥇31 ·  ⭐ 1.4K) - A library for training and deploying machine learning.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/aws/sagemaker-python-sdk) (👨‍💻 200 · 🔀 600 · 📦 680 · 📋 790 - 31% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/aws/sagemaker-python-sdk
	```
- [PyPi](https://pypi.org/project/sagemaker) (📥 810K / month):
	```
	pip install sagemaker
	```
</details>
<details><summary><b><a href="https://github.com/mlflow/mlflow">mlflow</a></b> (🥇30 ·  ⭐ 9K) - Open source platform for the machine learning lifecycle. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/mlflow/mlflow) (👨‍💻 290 · 🔀 1.9K · 📋 1.7K - 35% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/mlflow/mlflow
	```
- [PyPi](https://pypi.org/project/mlflow) (📥 4.8M / month):
	```
	pip install mlflow
	```
- [Conda](https://anaconda.org/conda-forge/mlflow) (📥 290K · ⏱️ 27.04.2021):
	```
	conda install -c conda-forge mlflow
	```
</details>
<details><summary><b><a href="https://github.com/lanpa/tensorboardX">tensorboardX</a></b> (🥇30 ·  ⭐ 6.9K) - tensorboard for pytorch (and chainer, mxnet, numpy, ...). <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/lanpa/tensorboardX) (👨‍💻 65 · 🔀 790 · 📥 320 · 📦 12K · 📋 410 - 13% open · ⏱️ 03.04.2021):

	```
	git clone https://github.com/lanpa/tensorboardX
	```
- [PyPi](https://pypi.org/project/tensorboardX) (📥 780K / month):
	```
	pip install tensorboardX
	```
- [Conda](https://anaconda.org/conda-forge/tensorboardx) (📥 350K · ⏱️ 06.04.2021):
	```
	conda install -c conda-forge tensorboardx
	```
</details>
<details><summary><b><a href="https://github.com/wandb/client">wandb client</a></b> (🥇30 ·  ⭐ 2.9K) - A tool for visualizing and tracking your machine learning.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/wandb/client) (👨‍💻 79 · 🔀 210 · 📦 2.7K · 📋 1K - 23% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/wandb/client
	```
- [PyPi](https://pypi.org/project/wandb) (📥 380K / month):
	```
	pip install wandb
	```
</details>
<details><summary><b><a href="https://github.com/IDSIA/sacred">sacred</a></b> (🥈29 ·  ⭐ 3.4K) - Sacred is a tool to help you configure, organize, log and reproduce.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/IDSIA/sacred) (👨‍💻 92 · 🔀 310 · 📦 890 · 📋 490 - 18% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/IDSIA/sacred
	```
- [PyPi](https://pypi.org/project/sacred) (📥 24K / month):
	```
	pip install sacred
	```
</details>
<details><summary><b><a href="https://github.com/snakemake/snakemake">snakemake</a></b> (🥈28 ·  ⭐ 940) - This is the development home of the workflow management system.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/snakemake/snakemake) (👨‍💻 200 · 🔀 210 · 📦 800 · 📋 610 - 62% open · ⏱️ 22.04.2021):

	```
	git clone https://github.com/snakemake/snakemake
	```
- [PyPi](https://pypi.org/project/snakemake) (📥 20K / month):
	```
	pip install snakemake
	```
- [Conda](https://anaconda.org/bioconda/snakemake) (📥 290K · ⏱️ 22.04.2021):
	```
	conda install -c bioconda snakemake
	```
</details>
<details><summary><b><a href="https://github.com/Kaggle/kaggle-api">kaggle</a></b> (🥈27 ·  ⭐ 4K) - Official Kaggle API. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Kaggle/kaggle-api) (👨‍💻 36 · 🔀 790 · 📦 5.2K · 📋 280 - 58% open · ⏱️ 15.03.2021):

	```
	git clone https://github.com/Kaggle/kaggle-api
	```
- [PyPi](https://pypi.org/project/kaggle) (📥 170K / month):
	```
	pip install kaggle
	```
- [Conda](https://anaconda.org/conda-forge/kaggle) (📥 54K · ⏱️ 16.03.2021):
	```
	conda install -c conda-forge kaggle
	```
</details>
<details><summary><b><a href="https://github.com/pycaret/pycaret">PyCaret</a></b> (🥈27 ·  ⭐ 3.3K) - An open-source, low-code machine learning library in Python. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/pycaret/pycaret) (👨‍💻 49 · 🔀 700 · 📥 380 · 📦 860 · 📋 820 - 25% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/pycaret/pycaret
	```
- [PyPi](https://pypi.org/project/pycaret) (📥 58K / month):
	```
	pip install pycaret
	```
</details>
<details><summary><b><a href="https://github.com/catalyst-team/catalyst">Catalyst</a></b> (🥈27 ·  ⭐ 2.5K) - Accelerated deep learning R&D. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/catalyst-team/catalyst) (👨‍💻 85 · 🔀 310 · 📦 340 · 📋 300 - 4% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/catalyst-team/catalyst
	```
- [PyPi](https://pypi.org/project/catalyst) (📥 13K / month):
	```
	pip install catalyst
	```
</details>
<details><summary><b><a href="https://github.com/Netflix/metaflow">Metaflow</a></b> (🥈26 ·  ⭐ 4.3K) - Build and manage real-life data science projects with ease. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Netflix/metaflow) (👨‍💻 31 · 🔀 350 · 📦 120 · 📋 260 - 42% open · ⏱️ 22.04.2021):

	```
	git clone https://github.com/Netflix/metaflow
	```
- [PyPi](https://pypi.org/project/metaflow) (📥 47K / month):
	```
	pip install metaflow
	```
- [Conda](https://anaconda.org/conda-forge/metaflow) (📥 15K · ⏱️ 23.04.2021):
	```
	conda install -c conda-forge metaflow
	```
</details>
<details><summary><b><a href="https://github.com/allegroai/clearml">ClearML</a></b> (🥈26 ·  ⭐ 2.4K) - ClearML - Auto-Magical Suite of tools to streamline your ML.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/allegroai/clearml) (👨‍💻 28 · 🔀 330 · 📥 300 · 📦 31 · 📋 290 - 26% open · ⏱️ 25.04.2021):

	```
	git clone https://github.com/allegroai/clearml
	```
- [PyPi](https://pypi.org/project/clearml) (📥 17K / month):
	```
	pip install clearml
	```
- [Docker Hub](https://hub.docker.com/r/allegroai/trains) (📥 30K · ⏱️ 05.10.2020):
	```
	docker pull allegroai/trains
	```
</details>
<details><summary><b><a href="https://github.com/PaddlePaddle/VisualDL">VisualDL</a></b> (🥈25 ·  ⭐ 3.9K) - Deep Learning Visualization Toolkit. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PaddlePaddle/VisualDL) (👨‍💻 29 · 🔀 540 · 📥 110 · 📦 270 · 📋 350 - 8% open · ⏱️ 19.04.2021):

	```
	git clone https://github.com/PaddlePaddle/VisualDL
	```
- [PyPi](https://pypi.org/project/visualdl) (📥 12K / month):
	```
	pip install visualdl
	```
</details>
<details><summary><b><a href="https://github.com/Azure/MachineLearningNotebooks">AzureML SDK</a></b> (🥈25 ·  ⭐ 2.3K) - Python notebooks with ML and deep learning examples with Azure.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Azure/MachineLearningNotebooks) (👨‍💻 55 · 🔀 1.6K · 📥 410 · 📋 1K - 14% open · ⏱️ 19.04.2021):

	```
	git clone https://github.com/Azure/MachineLearningNotebooks
	```
- [PyPi](https://pypi.org/project/azureml-sdk) (📥 680K / month):
	```
	pip install azureml-sdk
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/tnt">TNT</a></b> (🥉24 ·  ⭐ 1.3K) - Simple tools for logging and visualizing, loading and training. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/tnt) (👨‍💻 35 · 🔀 190 · 📦 570 · 📋 58 - 41% open · ⏱️ 05.01.2021):

	```
	git clone https://github.com/pytorch/tnt
	```
- [PyPi](https://pypi.org/project/torchnet) (📥 11K / month):
	```
	pip install torchnet
	```
</details>
<details><summary><b><a href="https://github.com/google/ml-metadata">ml-metadata</a></b> (🥉24 ·  ⭐ 310) - For recording and retrieving metadata associated with ML.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google/ml-metadata) (👨‍💻 12 · 🔀 57 · 📥 1.3K · 📦 100 · 📋 62 - 29% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/google/ml-metadata
	```
- [PyPi](https://pypi.org/project/ml-metadata) (📥 390K / month):
	```
	pip install ml-metadata
	```
</details>
<details><summary><b><a href="https://github.com/instacart/lore">lore</a></b> (🥉21 ·  ⭐ 1.5K · 💤) - Lore makes machine learning approachable for Software Engineers and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/instacart/lore) (👨‍💻 22 · 🔀 120 · 📦 16 · 📋 33 - 45% open · ⏱️ 11.05.2020):

	```
	git clone https://github.com/instacart/lore
	```
- [PyPi](https://pypi.org/project/lore) (📥 2.6K / month):
	```
	pip install lore
	```
</details>
<details><summary><b><a href="https://github.com/stared/livelossplot">livelossplot</a></b> (🥉21 ·  ⭐ 1.1K) - Live training loss plot in Jupyter Notebook for Keras,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/stared/livelossplot) (👨‍💻 16 · 🔀 140 · 📦 510 · 📋 73 - 4% open · ⏱️ 07.02.2021):

	```
	git clone https://github.com/stared/livelossplot
	```
- [PyPi](https://pypi.org/project/livelossplot) (📥 31K / month):
	```
	pip install livelossplot
	```
</details>
<details><summary><b><a href="https://github.com/studioml/studio">Studio.ml</a></b> (🥉21 ·  ⭐ 370) - Studio: Simplify and expedite model building process. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/studioml/studio) (👨‍💻 21 · 🔀 49 · 📦 4 · 📋 250 - 22% open · ⏱️ 27.03.2021):

	```
	git clone https://github.com/studioml/studio
	```
- [PyPi](https://pypi.org/project/studioml) (📥 2.3K / month):
	```
	pip install studioml
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/tensorwatch">TensorWatch</a></b> (🥉20 ·  ⭐ 3.1K) - Debugging, monitoring and visualization for Python Machine Learning.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/tensorwatch) (👨‍💻 13 · 🔀 330 · 📦 47 · 📋 64 - 76% open · ⏱️ 15.01.2021):

	```
	git clone https://github.com/microsoft/tensorwatch
	```
- [PyPi](https://pypi.org/project/tensorwatch) (📥 4.8K / month):
	```
	pip install tensorwatch
	```
</details>
<details><summary><b><a href="https://github.com/huggingface/knockknock">knockknock</a></b> (🥉20 ·  ⭐ 2.1K · 💀) - Knock Knock: Get notified when your training ends with only two.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/huggingface/knockknock) (👨‍💻 18 · 🔀 160 · 📦 160 · 📋 33 - 36% open · ⏱️ 16.03.2020):

	```
	git clone https://github.com/huggingface/knockknock
	```
- [PyPi](https://pypi.org/project/knockknock) (📥 3.9K / month):
	```
	pip install knockknock
	```
- [Conda](https://anaconda.org/conda-forge/knockknock) (📥 6.3K · ⏱️ 17.03.2020):
	```
	conda install -c conda-forge knockknock
	```
</details>
<details><summary><b><a href="https://github.com/m3dev/gokart">gokart</a></b> (🥉20 ·  ⭐ 180) - A wrapper of the data pipeline library luigi. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/m3dev/gokart) (👨‍💻 25 · 🔀 30 · 📋 36 - 5% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/m3dev/gokart
	```
- [PyPi](https://pypi.org/project/gokart) (📥 1.1K / month):
	```
	pip install gokart
	```
</details>
<details><summary><b><a href="https://github.com/waleedka/hiddenlayer">hiddenlayer</a></b> (🥉19 ·  ⭐ 1.4K · 💤) - Neural network graphs and training metrics for.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/waleedka/hiddenlayer) (👨‍💻 6 · 🔀 200 · 📦 68 · 📋 77 - 57% open · ⏱️ 24.04.2020):

	```
	git clone https://github.com/waleedka/hiddenlayer
	```
- [PyPi](https://pypi.org/project/hiddenlayer) (📥 2.9K / month):
	```
	pip install hiddenlayer
	```
</details>
<details><summary><b><a href="https://github.com/guildai/guildai">Guild AI</a></b> (🥉19 ·  ⭐ 570) - Experiment tracking, ML developer tools. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/guildai/guildai) (👨‍💻 16 · 🔀 41 · 📦 27 · 📋 270 - 37% open · ⏱️ 12.04.2021):

	```
	git clone https://github.com/guildai/guildai
	```
- [PyPi](https://pypi.org/project/guildai) (📥 5.7K / month):
	```
	pip install guildai
	```
</details>
<details><summary><b><a href="https://github.com/lab-ml/labml">Labml</a></b> (🥉18 ·  ⭐ 540) - Monitor deep learning model training and hardware usage from your mobile.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/lab-ml/labml) (👨‍💻 6 · 🔀 38 · 📦 24 · 📋 10 - 40% open · ⏱️ 25.04.2021):

	```
	git clone https://github.com/lab-ml/labml
	```
- [PyPi](https://pypi.org/project/labml) (📥 1.8K / month):
	```
	pip install labml
	```
</details>
<details><summary><b><a href="https://github.com/awslabs/mxboard">MXBoard</a></b> (🥉18 ·  ⭐ 330 · 💀) - Logging MXNet data for visualization in TensorBoard. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/awslabs/mxboard) (👨‍💻 9 · 🔀 46 · 📦 100 · 📋 31 - 51% open · ⏱️ 24.01.2020):

	```
	git clone https://github.com/awslabs/mxboard
	```
- [PyPi](https://pypi.org/project/mxboard) (📥 2.6K / month):
	```
	pip install mxboard
	```
</details>
<details><summary><b><a href="https://github.com/TeamHG-Memex/tensorboard_logger">TensorBoard Logger</a></b> (🥉17 ·  ⭐ 610 · 💀) - Log TensorBoard events without touching TensorFlow. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/TeamHG-Memex/tensorboard_logger) (👨‍💻 5 · 🔀 52 · 📋 23 - 34% open · ⏱️ 21.10.2019):

	```
	git clone https://github.com/TeamHG-Memex/tensorboard_logger
	```
- [PyPi](https://pypi.org/project/tensorboard_logger) (📥 92K / month):
	```
	pip install tensorboard_logger
	```
</details>
<details><summary><b><a href="https://github.com/EducationalTestingService/skll">SKLL</a></b> (🥉16 ·  ⭐ 530) - SciKit-Learn Laboratory (SKLL) makes it easy to run machine.. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/EducationalTestingService/skll) (👨‍💻 35 · 🔀 62 · 📥 10 · 📦 30 · 📋 380 - 9% open · ⏱️ 13.04.2021):

	```
	git clone https://github.com/EducationalTestingService/skll
	```
- [PyPi](https://pypi.org/project/skll) (📥 820 / month):
	```
	pip install skll
	```
</details>
<details><summary><b><a href="https://github.com/MrPowers/quinn">quinn</a></b> (🥉16 ·  ⭐ 240) - pyspark methods to enhance developer productivity. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/MrPowers/quinn) (👨‍💻 6 · 🔀 28 · 📋 23 - 60% open · ⏱️ 09.02.2021):

	```
	git clone https://github.com/MrPowers/quinn
	```
- [PyPi](https://pypi.org/project/quinn) (📥 210K / month):
	```
	pip install quinn
	```
</details>
<details><summary><b><a href="https://github.com/datmo/datmo">datmo</a></b> (🥉15 ·  ⭐ 330 · 💀) - Open source production model management tool for data scientists. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/datmo/datmo) (👨‍💻 6 · 🔀 28 · 📦 5 · 📋 180 - 15% open · ⏱️ 29.11.2019):

	```
	git clone https://github.com/datmo/datmo
	```
- [PyPi](https://pypi.org/project/datmo) (📥 360 / month):
	```
	pip install datmo
	```
</details>
<details><summary><b><a href="https://github.com/minerva-ml/steppy">steppy</a></b> (🥉15 ·  ⭐ 130 · 💀) - Lightweight, Python library for fast and reproducible experimentation. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/minerva-ml/steppy) (👨‍💻 5 · 🔀 31 · 📦 39 · 📋 63 - 20% open · ⏱️ 23.11.2018):

	```
	git clone https://github.com/minerva-ml/steppy
	```
- [PyPi](https://pypi.org/project/steppy) (📥 140 / month):
	```
	pip install steppy
	```
</details>
<details><summary><b><a href="https://github.com/ModelChimp/modelchimp">ModelChimp</a></b> (🥉15 ·  ⭐ 120) - Experiment tracking for machine and deep learning projects. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/ModelChimp/modelchimp) (👨‍💻 3 · 🔀 12 · 📋 14 - 28% open · ⏱️ 15.02.2021):

	```
	git clone https://github.com/ModelChimp/modelchimp
	```
- [PyPi](https://pypi.org/project/modelchimp) (📥 190 / month):
	```
	pip install modelchimp
	```
- [Docker Hub](https://hub.docker.com/r/modelchimp/modelchimp-server) (📥 640 · ⏱️ 09.04.2019):
	```
	docker pull modelchimp/modelchimp-server
	```
</details>
<details><summary><b><a href="https://github.com/aimhubio/aim">aim</a></b> (🥉14 ·  ⭐ 1.1K) - Aim a super-easy way to record, search and compare 1000s of ML training.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/aimhubio/aim) (👨‍💻 10 · 🔀 58 · 📋 170 - 59% open · ⏱️ 20.04.2021):

	```
	git clone https://github.com/aimhubio/aim
	```
- [PyPi](https://pypi.org/project/aim) (📥 2.9K / month):
	```
	pip install aim
	```
</details>
<details><summary><b><a href="https://github.com/jrieke/traintool">traintool</a></b> (🥉9 ·  ⭐ 9) - Train off-the-shelf machine learning models in one.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/jrieke/traintool) (🔀 1 · ⏱️ 12.03.2021):

	```
	git clone https://github.com/jrieke/traintool
	```
- [PyPi](https://pypi.org/project/traintool) (📥 41 / month):
	```
	pip install traintool
	```
</details>
<br>

## Model Serialization & Conversion

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries to serialize models to files, convert between a variety of model formats, and optimize models for deployment._

<details><summary><b><a href="https://github.com/onnx/onnx">onnx</a></b> (🥇34 ·  ⭐ 10K) - Open standard for machine learning interoperability. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/onnx/onnx) (👨‍💻 200 · 🔀 1.8K · 📥 12K · 📦 2.9K · 📋 1.5K - 30% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/onnx/onnx
	```
- [PyPi](https://pypi.org/project/onnx) (📥 1.5M / month):
	```
	pip install onnx
	```
- [Conda](https://anaconda.org/conda-forge/onnx) (📥 220K · ⏱️ 19.04.2021):
	```
	conda install -c conda-forge onnx
	```
</details>
<details><summary><b><a href="https://github.com/apple/coremltools">Core ML Tools</a></b> (🥇27 ·  ⭐ 2.2K) - Core ML tools contain supporting tools for Core ML model.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/apple/coremltools) (👨‍💻 110 · 🔀 340 · 📥 2.6K · 📦 500 · 📋 700 - 49% open · ⏱️ 09.04.2021):

	```
	git clone https://github.com/apple/coremltools
	```
- [PyPi](https://pypi.org/project/coremltools) (📥 62K / month):
	```
	pip install coremltools
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/serve">TorchServe</a></b> (🥈26 ·  ⭐ 1.7K) - Model Serving on PyTorch. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/serve) (👨‍💻 67 · 🔀 270 · 📥 210 · 📦 41 · 📋 540 - 18% open · ⏱️ 22.04.2021):

	```
	git clone https://github.com/pytorch/serve
	```
- [PyPi](https://pypi.org/project/torchserve) (📥 9.9K / month):
	```
	pip install torchserve
	```
- [Conda](https://anaconda.org/pytorch/torchserve) (📥 8K · ⏱️ 18.03.2021):
	```
	conda install -c pytorch torchserve
	```
- [Docker Hub](https://hub.docker.com/r/pytorch/torchserve) (📥 58K · ⭐ 3 · ⏱️ 18.12.2020):
	```
	docker pull pytorch/torchserve
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/MMdnn">mmdnn</a></b> (🥈24 ·  ⭐ 5.3K · 💤) - MMdnn is a set of tools to help users inter-operate among different deep.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/MMdnn) (👨‍💻 85 · 🔀 940 · 📥 3.4K · 📦 52 · 📋 600 - 51% open · ⏱️ 14.08.2020):

	```
	git clone https://github.com/Microsoft/MMdnn
	```
- [PyPi](https://pypi.org/project/mmdnn) (📥 1K / month):
	```
	pip install mmdnn
	```
</details>
<details><summary><b><a href="https://github.com/cortexlabs/cortex">cortex</a></b> (🥈23 ·  ⭐ 7.5K) - Cost-effective serverless computing at scale. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/cortexlabs/cortex) (👨‍💻 21 · 🔀 560 · 📋 1K - 12% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/cortexlabs/cortex
	```
- [PyPi](https://pypi.org/project/cortex) (📥 1.7K / month):
	```
	pip install cortex
	```
</details>
<details><summary><b><a href="https://github.com/BayesWitnesses/m2cgen">m2cgen</a></b> (🥉22 ·  ⭐ 1.8K) - Transform ML models into a native code (Java, C, Python, Go, JavaScript,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/BayesWitnesses/m2cgen) (👨‍💻 12 · 🔀 150 · 📦 6 · 📋 68 - 36% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/BayesWitnesses/m2cgen
	```
- [PyPi](https://pypi.org/project/m2cgen) (📥 24K / month):
	```
	pip install m2cgen
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/hummingbird">Hummingbird</a></b> (🥉21 ·  ⭐ 2.4K) - Hummingbird compiles trained ML models into tensor computation for.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/hummingbird) (👨‍💻 20 · 🔀 170 · 📥 99 · 📦 15 · 📋 200 - 23% open · ⏱️ 24.04.2021):

	```
	git clone https://github.com/microsoft/hummingbird
	```
- [PyPi](https://pypi.org/project/hummingbird-ml) (📥 3.2K / month):
	```
	pip install hummingbird-ml
	```
</details>
<details><summary><b><a href="https://github.com/nok/sklearn-porter">sklearn-porter</a></b> (🥉18 ·  ⭐ 1K · 💀) - Transpile trained scikit-learn estimators to C, Java,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/nok/sklearn-porter) (👨‍💻 11 · 🔀 130 · 📋 65 - 55% open · ⏱️ 18.12.2019):

	```
	git clone https://github.com/nok/sklearn-porter
	```
- [PyPi](https://pypi.org/project/sklearn-porter) (📥 1.2K / month):
	```
	pip install sklearn-porter
	```
</details>
<details><summary><b><a href="https://github.com/larq/compute-engine">Larq Compute Engine</a></b> (🥉18 ·  ⭐ 140) - Highly optimized inference engine for Binarized.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/larq/compute-engine) (👨‍💻 15 · 🔀 22 · 📥 210 · 📦 2 · 📋 120 - 20% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/larq/compute-engine
	```
- [PyPi](https://pypi.org/project/larq-compute-engine) (📥 4.1K / month):
	```
	pip install larq-compute-engine
	```
</details>
<details><summary><b><a href="https://github.com/nerox8664/pytorch2keras">pytorch2keras</a></b> (🥉16 ·  ⭐ 700 · 💤) - PyTorch to Keras model convertor. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nerox8664/pytorch2keras) (👨‍💻 11 · 🔀 110 · 📦 20 · 📋 110 - 40% open · ⏱️ 14.05.2020):

	```
	git clone https://github.com/nerox8664/pytorch2keras
	```
- [PyPi](https://pypi.org/project/pytorch2keras) (📥 940 / month):
	```
	pip install pytorch2keras
	```
</details>
<details><summary><b><a href="https://github.com/riga/tfdeploy">tfdeploy</a></b> (🥉16 ·  ⭐ 350) - Deploy tensorflow graphs for fast evaluation and export to.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/riga/tfdeploy) (👨‍💻 4 · 🔀 37 · 📋 32 - 28% open · ⏱️ 08.01.2021):

	```
	git clone https://github.com/riga/tfdeploy
	```
- [PyPi](https://pypi.org/project/tfdeploy) (📥 190 / month):
	```
	pip install tfdeploy
	```
</details>
<br>

## Model Interpretability

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries to visualize, explain, debug, evaluate, and interpret machine learning models._

<details><summary><b><a href="https://github.com/slundberg/shap">shap</a></b> (🥇34 ·  ⭐ 12K) - A game theoretic approach to explain the output of any machine learning model. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/slundberg/shap) (👨‍💻 160 · 🔀 1.8K · 📦 2.4K · 📋 1.5K - 66% open · ⏱️ 06.04.2021):

	```
	git clone https://github.com/slundberg/shap
	```
- [PyPi](https://pypi.org/project/shap) (📥 2.8M / month):
	```
	pip install shap
	```
- [Conda](https://anaconda.org/conda-forge/shap) (📥 460K · ⏱️ 16.12.2020):
	```
	conda install -c conda-forge shap
	```
</details>
<details><summary><b><a href="https://github.com/marcotcr/lime">Lime</a></b> (🥇29 ·  ⭐ 8.7K) - Lime: Explaining the predictions of any machine learning classifier. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/marcotcr/lime) (👨‍💻 57 · 🔀 1.4K · 📦 1.2K · 📋 500 - 10% open · ⏱️ 12.01.2021):

	```
	git clone https://github.com/marcotcr/lime
	```
- [PyPi](https://pypi.org/project/lime) (📥 370K / month):
	```
	pip install lime
	```
- [Conda](https://anaconda.org/conda-forge/lime) (📥 71K · ⏱️ 28.06.2020):
	```
	conda install -c conda-forge lime
	```
</details>
<details><summary><b><a href="https://github.com/bmabey/pyLDAvis">pyLDAvis</a></b> (🥇29 ·  ⭐ 1.4K) - Python library for interactive topic model visualization. Port of.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/bmabey/pyLDAvis) (👨‍💻 32 · 🔀 300 · 📦 2K · 📋 140 - 50% open · ⏱️ 24.03.2021):

	```
	git clone https://github.com/bmabey/pyLDAvis
	```
- [PyPi](https://pypi.org/project/pyldavis) (📥 160K / month):
	```
	pip install pyldavis
	```
- [Conda](https://anaconda.org/conda-forge/pyldavis) (📥 24K · ⏱️ 24.03.2021):
	```
	conda install -c conda-forge pyldavis
	```
</details>
<details><summary><b><a href="https://github.com/interpretml/interpret">InterpretML</a></b> (🥇27 ·  ⭐ 3.7K) - Fit interpretable models. Explain blackbox machine learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/interpretml/interpret) (👨‍💻 23 · 🔀 450 · 📦 73 · 📋 190 - 35% open · ⏱️ 13.04.2021):

	```
	git clone https://github.com/interpretml/interpret
	```
- [PyPi](https://pypi.org/project/interpret) (📥 29K / month):
	```
	pip install interpret
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/lucid">Lucid</a></b> (🥇26 ·  ⭐ 4.2K) - A collection of infrastructure and tools for research in neural.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/lucid) (👨‍💻 40 · 🔀 560 · 📦 550 · 📋 160 - 39% open · ⏱️ 19.03.2021):

	```
	git clone https://github.com/tensorflow/lucid
	```
- [PyPi](https://pypi.org/project/lucid) (📥 1.7K / month):
	```
	pip install lucid
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/captum">Captum</a></b> (🥇26 ·  ⭐ 2.3K) - Model interpretability and understanding for PyTorch. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/captum) (👨‍💻 70 · 🔀 230 · 📦 160 · 📋 210 - 21% open · ⏱️ 23.04.2021):

	```
	git clone https://github.com/pytorch/captum
	```
- [PyPi](https://pypi.org/project/captum) (📥 19K / month):
	```
	pip install captum
	```
</details>
<details><summary><b><a href="https://github.com/reiinakano/scikit-plot">scikit-plot</a></b> (🥇26 ·  ⭐ 2.1K · 💀) - An intuitive library to add plotting functionality to.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/reiinakano/scikit-plot) (👨‍💻 13 · 🔀 250 · 📦 900 · 📋 57 - 31% open · ⏱️ 19.08.2018):

	```
	git clone https://github.com/reiinakano/scikit-plot
	```
- [PyPi](https://pypi.org/project/scikit-plot) (📥 120K / month):
	```
	pip install scikit-plot
	```
- [Conda](https://anaconda.org/conda-forge/scikit-plot) (📥 87K · ⏱️ 05.06.2019):
	```
	conda install -c conda-forge scikit-plot
	```
</details>
<details><summary><b><a href="https://github.com/Trusted-AI/AIF360">Fairness 360</a></b> (🥈25 ·  ⭐ 1.4K) - A comprehensive set of fairness metrics for datasets and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Trusted-AI/AIF360) (👨‍💻 43 · 🔀 430 · 📦 80 · 📋 91 - 41% open · ⏱️ 10.03.2021):

	```
	git clone https://github.com/Trusted-AI/AIF360
	```
- [PyPi](https://pypi.org/project/aif360) (📥 7.7K / month):
	```
	pip install aif360
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/model-analysis">Model Analysis</a></b> (🥈25 ·  ⭐ 1.1K) - Model analysis tools for TensorFlow. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/model-analysis) (👨‍💻 35 · 🔀 200 · 📋 55 - 32% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/tensorflow/model-analysis
	```
- [PyPi](https://pypi.org/project/tensorflow-model-analysis) (📥 5.7M / month):
	```
	pip install tensorflow-model-analysis
	```
</details>
<details><summary><b><a href="https://github.com/arviz-devs/arviz">arviz</a></b> (🥈25 ·  ⭐ 1K) - Exploratory analysis of Bayesian models with Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/arviz-devs/arviz) (👨‍💻 79 · 🔀 200 · 📥 98 · 📦 840 · 📋 580 - 20% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/arviz-devs/arviz
	```
- [PyPi](https://pypi.org/project/arviz) (📥 210K / month):
	```
	pip install arviz
	```
- [Conda](https://anaconda.org/conda-forge/arviz) (📥 260K · ⏱️ 20.04.2021):
	```
	conda install -c conda-forge arviz
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/dowhy">DoWhy</a></b> (🥈24 ·  ⭐ 2.9K) - DoWhy is a Python library for causal inference that supports explicit.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/dowhy) (👨‍💻 40 · 🔀 410 · 📥 23 · 📦 36 · 📋 110 - 21% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/Microsoft/dowhy
	```
- [PyPi](https://pypi.org/project/dowhy) (📥 21K / month):
	```
	pip install dowhy
	```
- [Conda](https://anaconda.org/conda-forge/dowhy) (📥 1.6K · ⏱️ 13.12.2020):
	```
	conda install -c conda-forge dowhy
	```
</details>
<details><summary><b><a href="https://github.com/parrt/dtreeviz">dtreeviz</a></b> (🥈24 ·  ⭐ 1.5K) - A python library for decision tree visualization and model interpretation. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/parrt/dtreeviz) (👨‍💻 16 · 🔀 200 · 📦 140 · 📋 92 - 16% open · ⏱️ 05.04.2021):

	```
	git clone https://github.com/parrt/dtreeviz
	```
- [PyPi](https://pypi.org/project/dtreeviz) (📥 29K / month):
	```
	pip install dtreeviz
	```
</details>
<details><summary><b><a href="https://github.com/DistrictDataLabs/yellowbrick">yellowbrick</a></b> (🥈23 ·  ⭐ 3.2K) - Visual analysis and diagnostic tools to facilitate machine.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/DistrictDataLabs/yellowbrick) (👨‍💻 97 · 🔀 470 · 📋 610 - 13% open · ⏱️ 22.04.2021):

	```
	git clone https://github.com/DistrictDataLabs/yellowbrick
	```
- [PyPi](https://pypi.org/project/yellowbrick) (📥 160K / month):
	```
	pip install yellowbrick
	```
</details>
<details><summary><b><a href="https://github.com/raghakot/keras-vis">keras-vis</a></b> (🥈23 ·  ⭐ 2.8K · 💤) - Neural network visualization toolkit for keras. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/raghakot/keras-vis) (👨‍💻 10 · 🔀 590 · 📦 910 · 📋 210 - 53% open · ⏱️ 20.04.2020):

	```
	git clone https://github.com/raghakot/keras-vis
	```
- [PyPi](https://pypi.org/project/keras-vis) (📥 3.1K / month):
	```
	pip install keras-vis
	```
</details>
<details><summary><b><a href="https://github.com/SeldonIO/alibi">Alibi</a></b> (🥈23 ·  ⭐ 970) - Algorithms for monitoring and explaining machine learning models. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/SeldonIO/alibi) (👨‍💻 13 · 🔀 120 · 📦 77 · 📋 170 - 44% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/SeldonIO/alibi
	```
- [PyPi](https://pypi.org/project/alibi) (📥 9.5K / month):
	```
	pip install alibi
	```
</details>
<details><summary><b><a href="https://github.com/philipperemy/keract">keract</a></b> (🥈23 ·  ⭐ 880) - Layers Outputs and Gradients in Keras. Made easy. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/philipperemy/keract) (👨‍💻 15 · 🔀 180 · 📦 75 · 📋 78 - 2% open · ⏱️ 24.01.2021):

	```
	git clone https://github.com/philipperemy/keract
	```
- [PyPi](https://pypi.org/project/keract) (📥 2.3K / month):
	```
	pip install keract
	```
</details>
<details><summary><b><a href="https://github.com/TeamHG-Memex/eli5">eli5</a></b> (🥈22 ·  ⭐ 2.3K · 💀) - A library for debugging/inspecting machine learning classifiers and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/TeamHG-Memex/eli5) (👨‍💻 14 · 🔀 290 · 📋 240 - 53% open · ⏱️ 22.01.2020):

	```
	git clone https://github.com/TeamHG-Memex/eli5
	```
- [PyPi](https://pypi.org/project/eli5) (📥 500K / month):
	```
	pip install eli5
	```
- [Conda](https://anaconda.org/conda-forge/eli5) (📥 93K · ⏱️ 25.01.2021):
	```
	conda install -c conda-forge eli5
	```
</details>
<details><summary><b><a href="https://github.com/sicara/tf-explain">tf-explain</a></b> (🥈22 ·  ⭐ 800) - Interpretability Methods for tf.keras models with Tensorflow 2.x. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/sicara/tf-explain) (👨‍💻 14 · 🔀 77 · 📦 69 · 📋 79 - 41% open · ⏱️ 19.04.2021):

	```
	git clone https://github.com/sicara/tf-explain
	```
- [PyPi](https://pypi.org/project/tf-explain) (📥 1.5K / month):
	```
	pip install tf-explain
	```
</details>
<details><summary><b><a href="https://github.com/fairlearn/fairlearn">fairlearn</a></b> (🥈22 ·  ⭐ 770) - A Python package to assess and improve fairness of machine.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/fairlearn/fairlearn) (👨‍💻 35 · 🔀 180 · 📋 190 - 36% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/fairlearn/fairlearn
	```
- [PyPi](https://pypi.org/project/fairlearn) (📥 17K / month):
	```
	pip install fairlearn
	```
- [Conda](https://anaconda.org/conda-forge/fairlearn) (📥 12K · ⏱️ 13.04.2021):
	```
	conda install -c conda-forge fairlearn
	```
</details>
<details><summary><b><a href="https://github.com/parrt/random-forest-importances">random-forest-importances</a></b> (🥈22 ·  ⭐ 440) - Code to compute permutation and drop-column.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/parrt/random-forest-importances) (👨‍💻 14 · 🔀 95 · 📦 70 · 📋 31 - 12% open · ⏱️ 30.01.2021):

	```
	git clone https://github.com/parrt/random-forest-importances
	```
- [PyPi](https://pypi.org/project/rfpimp) (📥 30K / month):
	```
	pip install rfpimp
	```
</details>
<details><summary><b><a href="https://github.com/oegedijk/explainerdashboard">explainerdashboard</a></b> (🥉21 ·  ⭐ 470) - Quickly build Explainable AI dashboards that show the inner.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/oegedijk/explainerdashboard) (👨‍💻 8 · 🔀 53 · 📦 18 · 📋 89 - 6% open · ⏱️ 13.04.2021):

	```
	git clone https://github.com/oegedijk/explainerdashboard
	```
- [PyPi](https://pypi.org/project/explainerdashboard) (📥 5.9K / month):
	```
	pip install explainerdashboard
	```
</details>
<details><summary><b><a href="https://github.com/quantumblacklabs/causalnex">CausalNex</a></b> (🥉20 ·  ⭐ 1.1K) - A Python library that helps data scientists to infer.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/quantumblacklabs/causalnex) (👨‍💻 18 · 🔀 120 · 📦 11 · 📋 74 - 47% open · ⏱️ 13.04.2021):

	```
	git clone https://github.com/quantumblacklabs/causalnex
	```
- [PyPi](https://pypi.org/project/causalnex) (📥 5.4K / month):
	```
	pip install causalnex
	```
</details>
<details><summary><b><a href="https://github.com/Trusted-AI/AIX360">Explainability 360</a></b> (🥉20 ·  ⭐ 820) - Interpretability and explainability of data and machine.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Trusted-AI/AIX360) (👨‍💻 27 · 🔀 170 · 📦 16 · 📋 44 - 56% open · ⏱️ 04.12.2020):

	```
	git clone https://github.com/Trusted-AI/AIX360
	```
- [PyPi](https://pypi.org/project/aix360) (📥 980 / month):
	```
	pip install aix360
	```
</details>
<details><summary><b><a href="https://github.com/ModelOriented/DALEX">DALEX</a></b> (🥉20 ·  ⭐ 810) - moDel Agnostic Language for Exploration and eXplanation. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/ModelOriented/DALEX) (👨‍💻 18 · 🔀 110 · 📦 11 · 📋 280 - 4% open · ⏱️ 25.04.2021):

	```
	git clone https://github.com/ModelOriented/DALEX
	```
- [PyPi](https://pypi.org/project/dalex) (📥 6.8K / month):
	```
	pip install dalex
	```
</details>
<details><summary><b><a href="https://github.com/andosa/treeinterpreter">TreeInterpreter</a></b> (🥉20 ·  ⭐ 660) - Package for interpreting scikit-learn's decision tree.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/andosa/treeinterpreter) (👨‍💻 11 · 🔀 130 · 📦 130 · 📋 22 - 81% open · ⏱️ 28.02.2021):

	```
	git clone https://github.com/andosa/treeinterpreter
	```
- [PyPi](https://pypi.org/project/treeinterpreter) (📥 170K / month):
	```
	pip install treeinterpreter
	```
</details>
<details><summary><b><a href="https://github.com/PAIR-code/what-if-tool">What-If Tool</a></b> (🥉20 ·  ⭐ 500) - Source code/webpage/demos for the What-If Tool. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/PAIR-code/what-if-tool) (👨‍💻 19 · 🔀 100 · 📋 74 - 50% open · ⏱️ 17.03.2021):

	```
	git clone https://github.com/PAIR-code/what-if-tool
	```
- [PyPi](https://pypi.org/project/witwidget) (📥 10K / month):
	```
	pip install witwidget
	```
- [NPM](https://www.npmjs.com/package/wit-widget) (📥 3.2K / month):
	```
	npm install wit-widget
	```
</details>
<details><summary><b><a href="https://github.com/edublancas/sklearn-evaluation">sklearn-evaluation</a></b> (🥉20 ·  ⭐ 300) - Machine learning model evaluation made easy: plots,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/edublancas/sklearn-evaluation) (👨‍💻 5 · 🔀 24 · 📦 27 · 📋 36 - 22% open · ⏱️ 28.03.2021):

	```
	git clone https://github.com/edublancas/sklearn-evaluation
	```
- [PyPi](https://pypi.org/project/sklearn-evaluation) (📥 640 / month):
	```
	pip install sklearn-evaluation
	```
</details>
<details><summary><b><a href="https://github.com/oracle/Skater">Skater</a></b> (🥉19 ·  ⭐ 970 · 💤) - Python Library for Model Interpretation/Explanations. <code><a href="https://tldrlegal.com/search?q=UPL-1.0">❗️UPL-1.0</a></code></summary>

- [GitHub](https://github.com/oracle/Skater) (👨‍💻 34 · 🔀 160 · 📋 160 - 39% open · ⏱️ 29.06.2020):

	```
	git clone https://github.com/oracle/Skater
	```
- [PyPi](https://pypi.org/project/skater) (📥 2K / month):
	```
	pip install skater
	```
- [Conda](https://anaconda.org/conda-forge/skater) (📥 38K · ⏱️ 01.11.2020):
	```
	conda install -c conda-forge skater
	```
</details>
<details><summary><b><a href="https://github.com/PAIR-code/lit">LIT</a></b> (🥉18 ·  ⭐ 2.5K) - The Language Interpretability Tool: Interactively analyze NLP models for.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/PAIR-code/lit) (👨‍💻 14 · 🔀 250 · 📦 3 · 📋 70 - 40% open · ⏱️ 05.04.2021):

	```
	git clone https://github.com/PAIR-code/lit
	```
- [PyPi](https://pypi.org/project/lit-nlp) (📥 520 / month):
	```
	pip install lit-nlp
	```
</details>
<details><summary><b><a href="https://github.com/marcotcr/checklist">checklist</a></b> (🥉18 ·  ⭐ 1.3K) - Beyond Accuracy: Behavioral Testing of NLP models with CheckList. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/marcotcr/checklist) (👨‍💻 10 · 🔀 120 · 📦 7 · ⏱️ 30.03.2021):

	```
	git clone https://github.com/marcotcr/checklist
	```
- [PyPi](https://pypi.org/project/checklist) (📥 1.2K / month):
	```
	pip install checklist
	```
</details>
<details><summary><b><a href="https://github.com/albermax/innvestigate">iNNvestigate</a></b> (🥉18 ·  ⭐ 800) - A toolbox to iNNvestigate neural networks' predictions!. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/albermax/innvestigate) (👨‍💻 18 · 🔀 180 · 📦 54 · 📋 210 - 37% open · ⏱️ 16.10.2020):

	```
	git clone https://github.com/albermax/innvestigate
	```
- [PyPi](https://pypi.org/project/innvestigate) (📥 480 / month):
	```
	pip install innvestigate
	```
</details>
<details><summary><b><a href="https://github.com/kundajelab/deeplift">deeplift</a></b> (🥉18 ·  ⭐ 520) - Public facing deeplift repo. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/kundajelab/deeplift) (👨‍💻 11 · 🔀 130 · 📦 44 · 📋 74 - 36% open · ⏱️ 11.11.2020):

	```
	git clone https://github.com/kundajelab/deeplift
	```
- [PyPi](https://pypi.org/project/deeplift) (📥 820 / month):
	```
	pip install deeplift
	```
</details>
<details><summary><b><a href="https://github.com/interpretml/DiCE">DiCE</a></b> (🥉18 ·  ⭐ 520) - Generate Diverse Counterfactual Explanations for any machine.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/interpretml/DiCE) (👨‍💻 10 · 🔀 72 · 📋 38 - 31% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/interpretml/DiCE
	```
- [PyPi](https://pypi.org/project/dice-ml) (📥 1.8K / month):
	```
	pip install dice-ml
	```
</details>
<details><summary><b><a href="https://github.com/dssg/aequitas">aequitas</a></b> (🥉18 ·  ⭐ 380 · 📉) - Bias and Fairness Audit Toolkit. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/dssg/aequitas) (👨‍💻 16 · 🔀 69 · 📦 71 · 📋 53 - 60% open · ⏱️ 23.02.2021):

	```
	git clone https://github.com/dssg/aequitas
	```
- [PyPi](https://pypi.org/project/aequitas) (📥 1.1K / month):
	```
	pip install aequitas
	```
</details>
<details><summary><b><a href="https://github.com/csinva/imodels">imodels</a></b> (🥉18 ·  ⭐ 210) - Interpretable ML package for concise, transparent, and accurate predictive.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/csinva/imodels) (👨‍💻 3 · 🔀 19 · 📦 7 · 📋 11 - 9% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/csinva/imodels
	```
- [PyPi](https://pypi.org/project/imodels) (📥 380 / month):
	```
	pip install imodels
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/fairness-indicators">fairness-indicators</a></b> (🥉18 ·  ⭐ 190) - Tensorflow's Fairness Evaluation and Visualization.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/fairness-indicators) (👨‍💻 20 · 🔀 52 · ⏱️ 22.04.2021):

	```
	git clone https://github.com/tensorflow/fairness-indicators
	```
- [PyPi](https://pypi.org/project/fairness-indicators) (📥 930 / month):
	```
	pip install fairness-indicators
	```
</details>
<details><summary><b><a href="https://github.com/EthicalML/xai">XAI</a></b> (🥉17 ·  ⭐ 620) - XAI - An eXplainability toolbox for machine learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/EthicalML/xai) (👨‍💻 3 · 🔀 94 · 📦 11 · 📋 7 - 57% open · ⏱️ 23.04.2021):

	```
	git clone https://github.com/EthicalML/xai
	```
- [PyPi](https://pypi.org/project/xai) (📥 3.2K / month):
	```
	pip install xai
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/tcav">tcav</a></b> (🥉17 ·  ⭐ 450) - Code for the TCAV ML interpretability project. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/tcav) (👨‍💻 18 · 🔀 100 · 📦 6 · 📋 49 - 8% open · ⏱️ 23.03.2021):

	```
	git clone https://github.com/tensorflow/tcav
	```
- [PyPi](https://pypi.org/project/tcav) (📥 170 / month):
	```
	pip install tcav
	```
</details>
<details><summary><b><a href="https://github.com/explainX/explainx">ExplainX.ai</a></b> (🥉17 ·  ⭐ 200) - Explainable AI framework for data scientists. Explain & debug any.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/explainX/explainx) (👨‍💻 4 · 🔀 33 · 📥 1 · 📋 24 - 29% open · ⏱️ 02.02.2021):

	```
	git clone https://github.com/explainX/explainx
	```
- [PyPi](https://pypi.org/project/explainx) (📥 1K / month):
	```
	pip install explainx
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/model-card-toolkit">model-card-toolkit</a></b> (🥉17 ·  ⭐ 190) - a tool that leverages rich metadata and lineage.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/tensorflow/model-card-toolkit) (👨‍💻 9 · 🔀 27 · 📦 2 · 📋 5 - 60% open · ⏱️ 20.04.2021):

	```
	git clone https://github.com/tensorflow/model-card-toolkit
	```
- [PyPi](https://pypi.org/project/model-card-toolkit) (📥 370 / month):
	```
	pip install model-card-toolkit
	```
</details>
<details><summary><b><a href="https://github.com/MisaOgura/flashtorch">FlashTorch</a></b> (🥉16 ·  ⭐ 580) - Visualization toolkit for neural networks in PyTorch! Demo --. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/MisaOgura/flashtorch) (👨‍💻 2 · 🔀 66 · 📦 6 · 📋 27 - 22% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/MisaOgura/flashtorch
	```
- [PyPi](https://pypi.org/project/flashtorch) (📥 260 / month):
	```
	pip install flashtorch
	```
</details>
<details><summary><b><a href="https://github.com/marcotcr/anchor">Anchor</a></b> (🥉14 ·  ⭐ 630) - Code for High-Precision Model-Agnostic Explanations paper. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/marcotcr/anchor) (👨‍💻 8 · 🔀 87 · 📋 61 - 24% open · ⏱️ 19.04.2021):

	```
	git clone https://github.com/marcotcr/anchor
	```
- [PyPi](https://pypi.org/project/anchor_exp) (📥 760 / month):
	```
	pip install anchor_exp
	```
</details>
<details><summary><b><a href="https://github.com/aerdem4/lofo-importance">LOFO</a></b> (🥉14 ·  ⭐ 320 · 💤) - Leave One Feature Out Importance. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/aerdem4/lofo-importance) (👨‍💻 3 · 🔀 40 · 📦 3 · 📋 12 - 16% open · ⏱️ 02.07.2020):

	```
	git clone https://github.com/aerdem4/lofo-importance
	```
- [PyPi](https://pypi.org/project/lofo-importance) (📥 210 / month):
	```
	pip install lofo-importance
	```
</details>
<details><summary><b><a href="https://github.com/SAP/contextual-ai">contextual-ai</a></b> (🥉14 ·  ⭐ 68) - Contextual AI adds explainability to different stages of.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/SAP/contextual-ai) (👨‍💻 10 · 🔀 9 · 📋 6 - 83% open · ⏱️ 25.01.2021):

	```
	git clone https://github.com/SAP/contextual-ai
	```
- [PyPi](https://pypi.org/project/contextual-ai) (📥 210 / month):
	```
	pip install contextual-ai
	```
</details>
<details><summary><b><a href="https://github.com/suinleelab/attributionpriors">Attribution Priors</a></b> (🥉13 ·  ⭐ 75) - Tools for training explainable models using.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/suinleelab/attributionpriors) (👨‍💻 6 · 🔀 6 · 📦 2 · ⏱️ 19.03.2021):

	```
	git clone https://github.com/suinleelab/attributionpriors
	```
- [PyPi](https://pypi.org/project/attributionpriors) (📥 98 / month):
	```
	pip install attributionpriors
	```
</details>
<details><summary><b><a href="https://github.com/intuit/bias-detector">bias-detector</a></b> (🥉13 ·  ⭐ 21 · 🐣) - Bias Detector is a python package for detecting bias in machine.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/intuit/bias-detector) (👨‍💻 3 · 🔀 4 · ⏱️ 25.04.2021):

	```
	git clone https://github.com/intuit/bias-detector
	```
- [PyPi](https://pypi.org/project/bias-detector) (📥 340 / month):
	```
	pip install bias-detector
	```
</details>
<br>

## Vector Similarity Search (ANN)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for Approximate Nearest Neighbor Search and Vector Indexing/Similarity Search._

🔗&nbsp;<b><a href="https://github.com/erikbern/ann-benchmarks">ANN Benchmarks</a></b> ( ⭐ 2.2K)  - Benchmarks of approximate nearest neighbor libraries in Python.

<details><summary><b><a href="https://github.com/spotify/annoy">Annoy</a></b> (🥇30 ·  ⭐ 8.4K) - Approximate Nearest Neighbors in C++/Python optimized for memory usage.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/spotify/annoy) (👨‍💻 68 · 🔀 890 · 📦 1.5K · 📋 310 - 11% open · ⏱️ 03.12.2020):

	```
	git clone https://github.com/spotify/annoy
	```
- [PyPi](https://pypi.org/project/annoy) (📥 570K / month):
	```
	pip install annoy
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/faiss">Faiss</a></b> (🥇29 ·  ⭐ 13K) - A library for efficient similarity search and clustering of dense vectors. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebookresearch/faiss) (👨‍💻 84 · 🔀 2.1K · 📦 360 · 📋 1.5K - 7% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/facebookresearch/faiss
	```
- [PyPi](https://pypi.org/project/pymilvus) (📥 15K / month):
	```
	pip install pymilvus
	```
- [Conda](https://anaconda.org/conda-forge/faiss) (📥 80K · ⏱️ 19.04.2021):
	```
	conda install -c conda-forge faiss
	```
</details>
<details><summary><b><a href="https://github.com/nmslib/nmslib">NMSLIB</a></b> (🥇29 ·  ⭐ 2.4K) - Non-Metric Space Library (NMSLIB): An efficient similarity search.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/nmslib/nmslib) (👨‍💻 44 · 🔀 340 · 📦 360 · 📋 360 - 11% open · ⏱️ 16.03.2021):

	```
	git clone https://github.com/nmslib/nmslib
	```
- [PyPi](https://pypi.org/project/nmslib) (📥 70K / month):
	```
	pip install nmslib
	```
- [Conda](https://anaconda.org/conda-forge/nmslib) (📥 25K · ⏱️ 08.01.2021):
	```
	conda install -c conda-forge nmslib
	```
</details>
<details><summary><b><a href="https://github.com/nmslib/hnswlib">hnswlib</a></b> (🥈26 ·  ⭐ 1.5K) - Header-only C++/python library for fast approximate nearest neighbors. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/nmslib/hnswlib) (👨‍💻 41 · 🔀 260 · 📦 110 · 📋 190 - 43% open · ⏱️ 04.02.2021):

	```
	git clone https://github.com/nmslib/hnswlib
	```
- [PyPi](https://pypi.org/project/hnswlib) (📥 37K / month):
	```
	pip install hnswlib
	```
</details>
<details><summary><b><a href="https://github.com/lmcinnes/pynndescent">PyNNDescent</a></b> (🥈25 ·  ⭐ 390) - A Python nearest neighbor descent for approximate nearest neighbors. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/lmcinnes/pynndescent) (👨‍💻 13 · 🔀 49 · 📦 420 · 📋 62 - 41% open · ⏱️ 12.03.2021):

	```
	git clone https://github.com/lmcinnes/pynndescent
	```
- [PyPi](https://pypi.org/project/pynndescent) (📥 380K / month):
	```
	pip install pynndescent
	```
- [Conda](https://anaconda.org/conda-forge/pynndescent) (📥 110K · ⏱️ 09.02.2021):
	```
	conda install -c conda-forge pynndescent
	```
</details>
<details><summary><b><a href="https://github.com/milvus-io/milvus">Milvus</a></b> (🥉24 ·  ⭐ 5.6K) - An open source embedding vector similarity search engine powered by.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/milvus-io/milvus) (👨‍💻 130 · 🔀 850 · 📋 2.2K - 9% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/milvus-io/milvus
	```
- [PyPi](https://pypi.org/project/pymilvus) (📥 15K / month):
	```
	pip install pymilvus
	```
- [Docker Hub](https://hub.docker.com/r/milvusdb/milvus) (📥 320K · ⭐ 11 · ⏱️ 05.03.2021):
	```
	docker pull milvusdb/milvus
	```
</details>
<details><summary><b><a href="https://github.com/plasticityai/magnitude">Magnitude</a></b> (🥉23 ·  ⭐ 1.4K · 💤) - A fast, efficient universal vector embedding utility package. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/plasticityai/magnitude) (👨‍💻 4 · 🔀 100 · 📦 190 · 📋 77 - 35% open · ⏱️ 17.07.2020):

	```
	git clone https://github.com/plasticityai/magnitude
	```
- [PyPi](https://pypi.org/project/pymagnitude) (📥 10K / month):
	```
	pip install pymagnitude
	```
</details>
<details><summary><b><a href="https://github.com/yahoojapan/NGT">NGT</a></b> (🥉19 ·  ⭐ 700) - Nearest Neighbor Search with Neighborhood Graph and Tree for High-.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/yahoojapan/NGT) (👨‍💻 11 · 🔀 73 · 📋 80 - 7% open · ⏱️ 14.04.2021):

	```
	git clone https://github.com/yahoojapan/NGT
	```
- [PyPi](https://pypi.org/project/ngt) (📥 11K / month):
	```
	pip install ngt
	```
</details>
<details><summary><b><a href="https://github.com/pixelogik/NearPy">NearPy</a></b> (🥉19 ·  ⭐ 670 · 💀) - Python framework for fast (approximated) nearest neighbour search in.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pixelogik/NearPy) (👨‍💻 18 · 🔀 140 · 📦 52 · 📋 61 - 37% open · ⏱️ 21.10.2018):

	```
	git clone https://github.com/pixelogik/NearPy
	```
- [PyPi](https://pypi.org/project/NearPy) (📥 2.6K / month):
	```
	pip install NearPy
	```
</details>
<details><summary><b><a href="https://github.com/kakao/n2">N2</a></b> (🥉19 ·  ⭐ 460) - TOROS N2 - lightweight approximate Nearest Neighbor library which runs fast.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/kakao/n2) (👨‍💻 17 · 🔀 52 · 📦 14 · 📋 28 - 21% open · ⏱️ 21.10.2020):

	```
	git clone https://github.com/kakao/n2
	```
- [PyPi](https://pypi.org/project/n2) (📥 2.7K / month):
	```
	pip install n2
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/pysparnn">PySparNN</a></b> (🥉11 ·  ⭐ 870 · 💀) - Approximate Nearest Neighbor Search for Sparse Data in Python!. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/facebookresearch/pysparnn) (👨‍💻 5 · 🔀 140 · 📋 28 - 50% open · ⏱️ 31.01.2018):

	```
	git clone https://github.com/facebookresearch/pysparnn
	```
</details>
<br>

## Probabilistics & Statistics

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries providing capabilities for probabilistic programming/reasoning, bayesian inference, gaussian processes, or statistics._

<details><summary><b><a href="https://github.com/pymc-devs/pymc3">PyMC3</a></b> (🥇30 ·  ⭐ 5.7K) - Probabilistic Programming in Python: Bayesian Modeling and.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/pymc-devs/pymc3) (👨‍💻 310 · 🔀 1.3K · 📥 160 · 📦 2.4K · 📋 2.2K - 8% open · ⏱️ 05.04.2021):

	```
	git clone https://github.com/pymc-devs/pymc3
	```
- [PyPi](https://pypi.org/project/pymc3) (📥 200K / month):
	```
	pip install pymc3
	```
- [Conda](https://anaconda.org/conda-forge/pymc3) (📥 270K · ⏱️ 15.03.2021):
	```
	conda install -c conda-forge pymc3
	```
</details>
<details><summary><b><a href="https://github.com/cornellius-gp/gpytorch">GPyTorch</a></b> (🥇29 ·  ⭐ 2.4K) - A highly efficient and modular implementation of Gaussian Processes.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/cornellius-gp/gpytorch) (👨‍💻 78 · 🔀 330 · 📦 260 · 📋 890 - 22% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/cornellius-gp/gpytorch
	```
- [PyPi](https://pypi.org/project/gpytorch) (📥 68K / month):
	```
	pip install gpytorch
	```
</details>
<details><summary><b><a href="https://github.com/hmmlearn/hmmlearn">hmmlearn</a></b> (🥇29 ·  ⭐ 2.2K) - Hidden Markov Models in Python, with scikit-learn like API. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/hmmlearn/hmmlearn) (👨‍💻 32 · 🔀 620 · 📦 950 · 📋 350 - 16% open · ⏱️ 16.04.2021):

	```
	git clone https://github.com/hmmlearn/hmmlearn
	```
- [PyPi](https://pypi.org/project/hmmlearn) (📥 160K / month):
	```
	pip install hmmlearn
	```
- [Conda](https://anaconda.org/conda-forge/hmmlearn) (📥 76K · ⏱️ 04.02.2021):
	```
	conda install -c conda-forge hmmlearn
	```
</details>
<details><summary><b><a href="https://github.com/pyro-ppl/pyro">Pyro</a></b> (🥈28 ·  ⭐ 6.9K) - Deep universal probabilistic programming with Python and PyTorch. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pyro-ppl/pyro) (👨‍💻 110 · 🔀 810 · 📦 430 · 📋 830 - 16% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/pyro-ppl/pyro
	```
- [PyPi](https://pypi.org/project/pyro-ppl) (📥 35K / month):
	```
	pip install pyro-ppl
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/probability">tensorflow-probability</a></b> (🥈28 ·  ⭐ 3.3K) - Probabilistic reasoning and statistical analysis in.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/probability) (👨‍💻 410 · 🔀 840 · 📦 1 · 📋 970 - 41% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/tensorflow/probability
	```
- [PyPi](https://pypi.org/project/tensorflow-probability) (📥 740K / month):
	```
	pip install tensorflow-probability
	```
- [Conda](https://anaconda.org/conda-forge/tensorflow-probability) (📥 34K · ⏱️ 20.04.2021):
	```
	conda install -c conda-forge tensorflow-probability
	```
</details>
<details><summary><b><a href="https://github.com/GPflow/GPflow">GPflow</a></b> (🥈27 ·  ⭐ 1.4K) - Gaussian processes in TensorFlow. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/GPflow/GPflow) (👨‍💻 70 · 🔀 390 · 📦 240 · 📋 690 - 12% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/GPflow/GPflow
	```
- [PyPi](https://pypi.org/project/gpflow) (📥 4.8K / month):
	```
	pip install gpflow
	```
- [Conda](https://anaconda.org/conda-forge/gpflow) (📥 8.7K · ⏱️ 06.11.2018):
	```
	conda install -c conda-forge gpflow
	```
</details>
<details><summary><b><a href="https://github.com/jmschrei/pomegranate">pomegranate</a></b> (🥈26 ·  ⭐ 2.7K) - Fast, flexible and easy to use probabilistic modelling in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jmschrei/pomegranate) (👨‍💻 62 · 🔀 480 · 📦 440 · 📋 600 - 7% open · ⏱️ 29.03.2021):

	```
	git clone https://github.com/jmschrei/pomegranate
	```
- [PyPi](https://pypi.org/project/pomegranate) (📥 45K / month):
	```
	pip install pomegranate
	```
- [Conda](https://anaconda.org/conda-forge/pomegranate) (📥 55K · ⏱️ 01.11.2020):
	```
	conda install -c conda-forge pomegranate
	```
</details>
<details><summary><b><a href="https://github.com/pgmpy/pgmpy">pgmpy</a></b> (🥈25 ·  ⭐ 1.8K) - Python Library for learning (Structure and Parameter) and inference.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pgmpy/pgmpy) (👨‍💻 91 · 🔀 560 · 📥 71 · 📦 220 · 📋 700 - 27% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/pgmpy/pgmpy
	```
- [PyPi](https://pypi.org/project/pgmpy) (📥 31K / month):
	```
	pip install pgmpy
	```
</details>
<details><summary><b><a href="https://github.com/rlabbe/filterpy">filterpy</a></b> (🥈25 ·  ⭐ 1.8K) - Python Kalman filtering and optimal estimation library. Implements.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/rlabbe/filterpy) (👨‍💻 33 · 🔀 420 · 📦 810 · 📋 180 - 17% open · ⏱️ 08.02.2021):

	```
	git clone https://github.com/rlabbe/filterpy
	```
- [PyPi](https://pypi.org/project/filterpy) (📥 40K / month):
	```
	pip install filterpy
	```
- [Conda](https://anaconda.org/conda-forge/filterpy) (📥 60K · ⏱️ 05.05.2020):
	```
	conda install -c conda-forge filterpy
	```
</details>
<details><summary><b><a href="https://github.com/pydata/patsy">patsy</a></b> (🥈25 ·  ⭐ 740 · 💀) - Describing statistical models in Python using symbolic formulas. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/pydata/patsy) (👨‍💻 13 · 🔀 79 · 📦 33K · 📋 120 - 57% open · ⏱️ 31.10.2018):

	```
	git clone https://github.com/pydata/patsy
	```
- [PyPi](https://pypi.org/project/patsy) (📥 2.6M / month):
	```
	pip install patsy
	```
- [Conda](https://anaconda.org/conda-forge/patsy) (📥 2.9M · ⏱️ 28.10.2018):
	```
	conda install -c conda-forge patsy
	```
</details>
<details><summary><b><a href="https://github.com/blei-lab/edward">Edward</a></b> (🥉23 ·  ⭐ 4.6K · 💀) - A probabilistic programming language in TensorFlow. Deep.. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/blei-lab/edward) (👨‍💻 87 · 🔀 750 · 📥 14 · 📦 220 · 📋 510 - 36% open · ⏱️ 25.07.2018):

	```
	git clone https://github.com/blei-lab/edward
	```
- [PyPi](https://pypi.org/project/edward) (📥 2.1K / month):
	```
	pip install edward
	```
</details>
<details><summary><b><a href="https://github.com/raphaelvallat/pingouin">pingouin</a></b> (🥉23 ·  ⭐ 700) - Statistical package in Python based on Pandas. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/raphaelvallat/pingouin) (👨‍💻 18 · 🔀 56 · 📦 210 · 📋 130 - 9% open · ⏱️ 14.04.2021):

	```
	git clone https://github.com/raphaelvallat/pingouin
	```
- [PyPi](https://pypi.org/project/pingouin) (📥 31K / month):
	```
	pip install pingouin
	```
- [Conda](https://anaconda.org/conda-forge/pingouin) (📥 36K · ⏱️ 14.04.2021):
	```
	conda install -c conda-forge pingouin
	```
</details>
<details><summary><b><a href="https://github.com/SALib/SALib">SALib</a></b> (🥉21 ·  ⭐ 450) - Sensitivity Analysis Library in Python (Numpy). Contains Sobol, Morris,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/SALib/SALib) (👨‍💻 25 · 🔀 140 · 📋 220 - 13% open · ⏱️ 21.04.2021):

	```
	git clone https://github.com/SALib/SALib
	```
- [PyPi](https://pypi.org/project/salib) (📥 23K / month):
	```
	pip install salib
	```
- [Conda](https://anaconda.org/conda-forge/salib) (📥 62K · ⏱️ 24.10.2020):
	```
	conda install -c conda-forge salib
	```
</details>
<details><summary><b><a href="https://github.com/bambinos/bambi">bambi</a></b> (🥉20 ·  ⭐ 600) - BAyesian Model-Building Interface (Bambi) in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/bambinos/bambi) (👨‍💻 16 · 🔀 50 · 📦 13 · 📋 170 - 18% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/bambinos/bambi
	```
- [PyPi](https://pypi.org/project/bambi) (📥 540 / month):
	```
	pip install bambi
	```
</details>
<details><summary><b><a href="https://github.com/maximtrp/scikit-posthocs">scikit-posthocs</a></b> (🥉20 ·  ⭐ 200) - Multiple Pairwise Comparisons (Post Hoc) Tests in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/maximtrp/scikit-posthocs) (👨‍💻 8 · 🔀 21 · 📥 19 · 📋 40 - 10% open · ⏱️ 15.03.2021):

	```
	git clone https://github.com/maximtrp/scikit-posthocs
	```
- [PyPi](https://pypi.org/project/scikit-posthocs) (📥 16K / month):
	```
	pip install scikit-posthocs
	```
</details>
<details><summary><b><a href="https://github.com/pyro-ppl/funsor">Funsor</a></b> (🥉19 ·  ⭐ 170) - Functional tensors for probabilistic programming. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pyro-ppl/funsor) (👨‍💻 9 · 🔀 14 · 📦 13 · 📋 130 - 46% open · ⏱️ 16.04.2021):

	```
	git clone https://github.com/pyro-ppl/funsor
	```
- [PyPi](https://pypi.org/project/funsor) (📥 530 / month):
	```
	pip install funsor
	```
</details>
<details><summary><b><a href="https://github.com/mattjj/pyhsmm">pyhsmm</a></b> (🥉18 ·  ⭐ 490 · 💤) - Bayesian inference in HSMMs and HMMs. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mattjj/pyhsmm) (👨‍💻 13 · 🔀 150 · 📦 18 · 📋 94 - 36% open · ⏱️ 24.08.2020):

	```
	git clone https://github.com/mattjj/pyhsmm
	```
- [PyPi](https://pypi.org/project/pyhsmm) (📥 240 / month):
	```
	pip install pyhsmm
	```
</details>
<details><summary><b><a href="https://github.com/ElementAI/baal">Baal</a></b> (🥉18 ·  ⭐ 340) - Using approximate bayesian posteriors in deep nets for active learning. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/ElementAI/baal) (👨‍💻 8 · 🔀 31 · 📦 7 · 📋 40 - 22% open · ⏱️ 22.04.2021):

	```
	git clone https://github.com/ElementAI/baal
	```
- [PyPi](https://pypi.org/project/baal) (📥 420 / month):
	```
	pip install baal
	```
</details>
<details><summary><b><a href="https://github.com/uber/orbit">Orbit</a></b> (🥉17 ·  ⭐ 400) - A Python package for Bayesian forecasting with object-oriented.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/uber/orbit) (👨‍💻 9 · 🔀 28 · 📦 4 · 📋 200 - 8% open · ⏱️ 15.04.2021):

	```
	git clone https://github.com/uber/orbit
	```
- [PyPi](https://pypi.org/project/orbit-ml) (📥 380 / month):
	```
	pip install orbit-ml
	```
</details>
<details><summary><b><a href="https://github.com/stan-dev/pystan">PyStan</a></b> (🥉16 ·  ⭐ 66) - PyStan, a Python interface to Stan, a platform for statistical modeling... <code><a href="http://bit.ly/3hkKRql">ISC</a></code></summary>

- [GitHub](https://github.com/stan-dev/pystan) (👨‍💻 7 · 🔀 16 · 📋 130 - 10% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/stan-dev/pystan
	```
- [PyPi](https://pypi.org/project/pystan) (📥 1.1M / month):
	```
	pip install pystan
	```
- [Conda](https://anaconda.org/conda-forge/pystan) (📥 960K · ⏱️ 25.08.2020):
	```
	conda install -c conda-forge pystan
	```
</details>
<details><summary><b><a href="https://github.com/thu-ml/zhusuan">ZhuSuan</a></b> (🥉14 ·  ⭐ 2K · 💀) - A probabilistic programming library for Bayesian deep learning,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/thu-ml/zhusuan) (👨‍💻 20 · 🔀 390 · 📋 60 - 11% open · ⏱️ 05.08.2019):

	```
	git clone https://github.com/thu-ml/zhusuan
	```
</details>
<br>

## Adversarial Robustness

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for testing the robustness of machine learning models against attacks with adversarial/malicious examples._

<details><summary><b><a href="https://github.com/cleverhans-lab/cleverhans">CleverHans</a></b> (🥇27 ·  ⭐ 5.1K) - An adversarial example library for constructing attacks,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/cleverhans-lab/cleverhans) (👨‍💻 120 · 🔀 1.2K · 📦 210 · 📋 430 - 3% open · ⏱️ 20.04.2021):

	```
	git clone https://github.com/cleverhans-lab/cleverhans
	```
- [PyPi](https://pypi.org/project/cleverhans) (📥 820 / month):
	```
	pip install cleverhans
	```
</details>
<details><summary><b><a href="https://github.com/bethgelab/foolbox">Foolbox</a></b> (🥈26 ·  ⭐ 1.9K) - A Python toolbox to create adversarial examples that fool neural networks.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/bethgelab/foolbox) (👨‍💻 31 · 🔀 340 · 📦 180 · 📋 310 - 15% open · ⏱️ 19.03.2021):

	```
	git clone https://github.com/bethgelab/foolbox
	```
- [PyPi](https://pypi.org/project/foolbox) (📥 2.6K / month):
	```
	pip install foolbox
	```
</details>
<details><summary><b><a href="https://github.com/QData/TextAttack">TextAttack</a></b> (🥈25 ·  ⭐ 1.4K) - TextAttack is a Python framework for adversarial attacks, data.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/QData/TextAttack) (👨‍💻 34 · 🔀 160 · 📦 22 · 📋 120 - 33% open · ⏱️ 23.04.2021):

	```
	git clone https://github.com/QData/TextAttack
	```
- [PyPi](https://pypi.org/project/textattack) (📥 2.6K / month):
	```
	pip install textattack
	```
</details>
<details><summary><b><a href="https://github.com/Trusted-AI/adversarial-robustness-toolbox">ART</a></b> (🥉23 ·  ⭐ 2.2K) - Adversarial Robustness Toolbox (ART) - Python Library for Machine Learning.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Trusted-AI/adversarial-robustness-toolbox) (👨‍💻 66 · 🔀 600 · 📦 110 · 📋 480 - 11% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/Trusted-AI/adversarial-robustness-toolbox
	```
- [PyPi](https://pypi.org/project/adversarial-robustness-toolbox) (📥 4.3K / month):
	```
	pip install adversarial-robustness-toolbox
	```
</details>
<details><summary><b><a href="https://github.com/MadryLab/robustness">robustness</a></b> (🥉19 ·  ⭐ 520) - A library for experimenting with, training and evaluating neural.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/MadryLab/robustness) (👨‍💻 12 · 🔀 95 · 📦 46 · 📋 58 - 12% open · ⏱️ 04.03.2021):

	```
	git clone https://github.com/MadryLab/robustness
	```
- [PyPi](https://pypi.org/project/robustness) (📥 460 / month):
	```
	pip install robustness
	```
</details>
<details><summary><b><a href="https://github.com/BorealisAI/advertorch">advertorch</a></b> (🥉17 ·  ⭐ 850 · 💤) - A Toolbox for Adversarial Robustness Research. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/BorealisAI/advertorch) (👨‍💻 16 · 🔀 130 · 📦 36 · 📋 41 - 31% open · ⏱️ 15.06.2020):

	```
	git clone https://github.com/BorealisAI/advertorch
	```
- [PyPi](https://pypi.org/project/advertorch) (📥 1.8K / month):
	```
	pip install advertorch
	```
</details>
<details><summary><b><a href="https://github.com/advboxes/AdvBox">AdvBox</a></b> (🥉15 ·  ⭐ 1.1K · 💤) - Advbox is a toolbox to generate adversarial examples that fool.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/advboxes/AdvBox) (👨‍💻 19 · 🔀 230 · 📋 31 - 9% open · ⏱️ 26.08.2020):

	```
	git clone https://github.com/advboxes/AdvBox
	```
- [PyPi](https://pypi.org/project/advbox) (📥 77 / month):
	```
	pip install advbox
	```
</details>
<br>

## GPU Utilities

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries that require and make use of CUDA/GPU system capabilities to optimize data handling and machine learning tasks._

<details><summary><b><a href="https://github.com/cupy/cupy">CuPy</a></b> (🥇31 ·  ⭐ 5.1K) - A NumPy-compatible array library accelerated by CUDA. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/cupy/cupy) (👨‍💻 260 · 🔀 440 · 📥 15K · 📦 720 · 📋 1.3K - 22% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/cupy/cupy
	```
- [PyPi](https://pypi.org/project/cupy) (📥 88K / month):
	```
	pip install cupy
	```
- [Conda](https://anaconda.org/conda-forge/cupy) (📥 540K · ⏱️ 23.04.2021):
	```
	conda install -c conda-forge cupy
	```
- [Docker Hub](https://hub.docker.com/r/cupy/cupy) (📥 50K · ⭐ 6 · ⏱️ 28.04.2021):
	```
	docker pull cupy/cupy
	```
</details>
<details><summary><b><a href="https://github.com/wookayin/gpustat">gpustat</a></b> (🥇26 ·  ⭐ 2.3K) - A simple command-line utility for querying and monitoring GPU status. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/wookayin/gpustat) (👨‍💻 12 · 🔀 180 · 📦 800 · 📋 64 - 23% open · ⏱️ 23.03.2021):

	```
	git clone https://github.com/wookayin/gpustat
	```
- [PyPi](https://pypi.org/project/gpustat) (📥 400K / month):
	```
	pip install gpustat
	```
- [Conda](https://anaconda.org/conda-forge/gpustat) (📥 50K · ⏱️ 24.11.2020):
	```
	conda install -c conda-forge gpustat
	```
</details>
<details><summary><b><a href="https://github.com/NVIDIA/apex">Apex</a></b> (🥈23 ·  ⭐ 5.3K) - A PyTorch Extension: Tools for easy mixed precision and distributed.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/NVIDIA/apex) (👨‍💻 82 · 🔀 710 · 📦 540 · 📋 820 - 54% open · ⏱️ 19.04.2021):

	```
	git clone https://github.com/NVIDIA/apex
	```
- [Conda](https://anaconda.org/conda-forge/nvidia-apex) (📥 42K · ⏱️ 22.04.2021):
	```
	conda install -c conda-forge nvidia-apex
	```
</details>
<details><summary><b><a href="https://github.com/anderskm/gputil">GPUtil</a></b> (🥈23 ·  ⭐ 710 · 💀) - A Python module for getting the GPU status from NVIDA GPUs using.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/anderskm/gputil) (👨‍💻 13 · 🔀 79 · 📦 1.1K · 📋 25 - 44% open · ⏱️ 16.08.2019):

	```
	git clone https://github.com/anderskm/gputil
	```
- [PyPi](https://pypi.org/project/gputil) (📥 100K / month):
	```
	pip install gputil
	```
</details>
<details><summary><b><a href="https://github.com/fbcotter/py3nvml">py3nvml</a></b> (🥈22 ·  ⭐ 170 · 💤) - Python 3 Bindings for NVML library. Get NVIDIA GPU status inside.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/fbcotter/py3nvml) (👨‍💻 6 · 🔀 21 · 📦 250 · 📋 11 - 9% open · ⏱️ 23.04.2020):

	```
	git clone https://github.com/fbcotter/py3nvml
	```
- [PyPi](https://pypi.org/project/py3nvml) (📥 110K / month):
	```
	pip install py3nvml
	```
- [Conda](https://anaconda.org/conda-forge/py3nvml) (📥 16K · ⏱️ 10.10.2020):
	```
	conda install -c conda-forge py3nvml
	```
</details>
<details><summary><b><a href="https://github.com/rapidsai/cudf">cuDF</a></b> (🥈21 ·  ⭐ 3.9K) - cuDF - GPU DataFrame Library. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/rapidsai/cudf) (👨‍💻 210 · 🔀 500 · 📋 3.6K - 15% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/rapidsai/cudf
	```
- [PyPi](https://pypi.org/project/cudf) (📥 1.7K / month):
	```
	pip install cudf
	```
</details>
<details><summary><b><a href="https://github.com/arrayfire/arrayfire">ArrayFire</a></b> (🥈21 ·  ⭐ 3.4K) - ArrayFire: a general purpose GPU library. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/arrayfire/arrayfire) (👨‍💻 80 · 🔀 460 · 📥 1.1K · 📋 1.5K - 15% open · ⏱️ 23.03.2021):

	```
	git clone https://github.com/arrayfire/arrayfire
	```
- [PyPi](https://pypi.org/project/arrayfire) (📥 1.1K / month):
	```
	pip install arrayfire
	```
</details>
<details><summary><b><a href="https://github.com/NVIDIA/DALI">DALI</a></b> (🥉20 ·  ⭐ 3.2K) - A GPU-accelerated library containing highly optimized building blocks.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/NVIDIA/DALI) (👨‍💻 57 · 🔀 380 · 📋 890 - 11% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/NVIDIA/DALI
	```
</details>
<details><summary><b><a href="https://github.com/inducer/pycuda">PyCUDA</a></b> (🥉20 ·  ⭐ 1.1K) - CUDA integration for Python, plus shiny features. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/inducer/pycuda) (👨‍💻 70 · 🔀 220 · 📦 810 · 📋 180 - 25% open · ⏱️ 16.04.2021):

	```
	git clone https://github.com/inducer/pycuda
	```
- [PyPi](https://pypi.org/project/pycuda) (📥 54K / month):
	```
	pip install pycuda
	```
</details>
<details><summary><b><a href="https://github.com/lebedov/scikit-cuda">scikit-cuda</a></b> (🥉20 ·  ⭐ 820) - Python interface to GPU-powered libraries. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/lebedov/scikit-cuda) (👨‍💻 44 · 🔀 160 · 📦 130 · 📋 210 - 20% open · ⏱️ 30.03.2021):

	```
	git clone https://github.com/lebedov/scikit-cuda
	```
- [PyPi](https://pypi.org/project/scikit-cuda) (📥 850 / month):
	```
	pip install scikit-cuda
	```
</details>
<details><summary><b><a href="https://github.com/rapidsai/cuml">cuML</a></b> (🥉19 ·  ⭐ 2.1K) - cuML - RAPIDS Machine Learning Library. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/rapidsai/cuml) (👨‍💻 130 · 🔀 330 · 📋 1.7K - 34% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/rapidsai/cuml
	```
- [PyPi](https://pypi.org/project/cuml) (📥 950 / month):
	```
	pip install cuml
	```
</details>
<details><summary><b><a href="https://github.com/EthicalML/vulkan-kompute">Vulkan Kompute</a></b> (🥉18 ·  ⭐ 380) - General purpose GPU compute framework for cross vendor.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/EthicalML/vulkan-kompute) (👨‍💻 11 · 🔀 29 · 📥 51 · 📦 2 · 📋 140 - 31% open · ⏱️ 24.04.2021):

	```
	git clone https://github.com/EthicalML/vulkan-kompute
	```
- [PyPi](https://pypi.org/project/kp) (📥 210 / month):
	```
	pip install kp
	```
</details>
<details><summary><b><a href="https://github.com/BlazingDB/blazingsql">BlazingSQL</a></b> (🥉17 ·  ⭐ 1.5K) - BlazingSQL is a lightweight, GPU accelerated, SQL engine for.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/BlazingDB/blazingsql) (👨‍💻 42 · 🔀 140 · 📋 670 - 16% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/BlazingDB/blazingsql
	```
- [Conda](https://anaconda.org/blazingsql/blazingsql-protocol) (📥 920 · ⏱️ 11.11.2019):
	```
	conda install -c blazingsql blazingsql-protocol
	```
</details>
<details><summary><b><a href="https://github.com/rapidsai/cugraph">cuGraph</a></b> (🥉16 ·  ⭐ 700) - cuGraph - RAPIDS Graph Analytics Library. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/rapidsai/cugraph) (👨‍💻 61 · 🔀 140 · 📋 640 - 15% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/rapidsai/cugraph
	```
- [PyPi](https://pypi.org/project/cugraph) (📥 120 / month):
	```
	pip install cugraph
	```
</details>
<details><summary><b><a href="https://github.com/nicolargo/nvidia-ml-py3">nvidia-ml-py3</a></b> (🥉16 ·  ⭐ 67 · 💀) - Python 3 Bindings for the NVIDIA Management Library. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/nicolargo/nvidia-ml-py3) (👨‍💻 2 · 🔀 14 · 📦 3.1K · ⏱️ 06.03.2019):

	```
	git clone https://github.com/nicolargo/nvidia-ml-py3
	```
- [PyPi](https://pypi.org/project/nvidia-ml-py3) (📥 690K / month):
	```
	pip install nvidia-ml-py3
	```
</details>
<details><summary><b><a href="https://github.com/Santosh-Gupta/SpeedTorch">SpeedTorch</a></b> (🥉15 ·  ⭐ 620 · 💀) - Library for faster pinned CPU - GPU transfer in Pytorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/Santosh-Gupta/SpeedTorch) (👨‍💻 3 · 🔀 37 · 📦 3 · 📋 5 - 60% open · ⏱️ 21.02.2020):

	```
	git clone https://github.com/Santosh-Gupta/SpeedTorch
	```
- [PyPi](https://pypi.org/project/SpeedTorch) (📥 200 / month):
	```
	pip install SpeedTorch
	```
</details>
<details><summary><b><a href="https://github.com/rapidsai/cusignal">cuSignal</a></b> (🥉15 ·  ⭐ 480) - GPU accelerated signal processing. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/rapidsai/cusignal) (👨‍💻 30 · 🔀 62 · 📋 100 - 7% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/rapidsai/cusignal
	```
</details>
<details><summary><b><a href="https://github.com/stas00/ipyexperiments">ipyexperiments</a></b> (🥉12 ·  ⭐ 130) - jupyter/ipython experiment containers for GPU and.. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/stas00/ipyexperiments) (👨‍💻 3 · 🔀 9 · 📦 5 · ⏱️ 28.03.2021):

	```
	git clone https://github.com/stas00/ipyexperiments
	```
- [PyPi](https://pypi.org/project/ipyexperiments) (📥 400 / month):
	```
	pip install ipyexperiments
	```
</details>
<br>

## Tensorflow Utilities

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries that extend TensorFlow with additional capabilities._

<details><summary><b><a href="https://github.com/tensorflow/tensor2tensor">tensor2tensor</a></b> (🥇32 ·  ⭐ 11K) - Library of deep learning models and datasets designed to.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/tensor2tensor) (👨‍💻 230 · 🔀 2.8K · 📦 960 · 📋 1.2K - 45% open · ⏱️ 05.03.2021):

	```
	git clone https://github.com/tensorflow/tensor2tensor
	```
- [PyPi](https://pypi.org/project/tensor2tensor) (📥 91K / month):
	```
	pip install tensor2tensor
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/hub">tensorflow-hub</a></b> (🥇32 ·  ⭐ 2.8K) - A library for transfer learning by reusing parts of.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/hub) (👨‍💻 69 · 🔀 1.5K · 📦 6.3K · 📋 570 - 5% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/tensorflow/hub
	```
- [PyPi](https://pypi.org/project/tensorflow-hub) (📥 1.6M / month):
	```
	pip install tensorflow-hub
	```
- [Conda](https://anaconda.org/conda-forge/tensorflow-hub) (📥 52K · ⏱️ 18.04.2021):
	```
	conda install -c conda-forge tensorflow-hub
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/addons">TF Addons</a></b> (🥇32 ·  ⭐ 1.3K) - Useful extra functionality for TensorFlow 2.x maintained by.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/addons) (👨‍💻 160 · 🔀 420 · 📦 2.8K · 📋 790 - 18% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/tensorflow/addons
	```
- [PyPi](https://pypi.org/project/tensorflow-addons) (📥 1.1M / month):
	```
	pip install tensorflow-addons
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/transform">TensorFlow Transform</a></b> (🥈29 ·  ⭐ 860) - Input pipeline framework. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/transform) (👨‍💻 27 · 🔀 170 · 📦 440 · 📋 160 - 15% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/tensorflow/transform
	```
- [PyPi](https://pypi.org/project/tensorflow-transform) (📥 7.3M / month):
	```
	pip install tensorflow-transform
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/model-optimization">TF Model Optimization</a></b> (🥈26 ·  ⭐ 1K) - A toolkit to optimize ML models for deployment for.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/model-optimization) (👨‍💻 49 · 🔀 230 · 📦 750 · 📋 180 - 34% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/tensorflow/model-optimization
	```
- [PyPi](https://pypi.org/project/tensorflow-model-optimization) (📥 140K / month):
	```
	pip install tensorflow-model-optimization
	```
</details>
<details><summary><b><a href="https://github.com/qubvel/efficientnet">efficientnet</a></b> (🥉25 ·  ⭐ 1.8K · 💤) - Implementation of EfficientNet model. Keras and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/qubvel/efficientnet) (👨‍💻 8 · 🔀 400 · 📥 170K · 📦 580 · 📋 100 - 46% open · ⏱️ 15.09.2020):

	```
	git clone https://github.com/qubvel/efficientnet
	```
- [PyPi](https://pypi.org/project/efficientnet) (📥 120K / month):
	```
	pip install efficientnet
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/cloud">TensorFlow Cloud</a></b> (🥉24 ·  ⭐ 240) - The TensorFlow Cloud repository provides APIs that.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/cloud) (👨‍💻 18 · 🔀 47 · 📦 48 · 📋 67 - 62% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/tensorflow/cloud
	```
- [PyPi](https://pypi.org/project/tensorflow-cloud) (📥 210K / month):
	```
	pip install tensorflow-cloud
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/io">TensorFlow I/O</a></b> (🥉23 ·  ⭐ 450 · 📉) - Dataset, streaming, and file system extensions.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/io) (👨‍💻 73 · 🔀 150 · 📋 410 - 31% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/tensorflow/io
	```
- [PyPi](https://pypi.org/project/tensorflow-io) (📥 120K / month):
	```
	pip install tensorflow-io
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/neural-structured-learning">Neural Structured Learning</a></b> (🥉22 ·  ⭐ 810) - Training neural models with structured signals. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/neural-structured-learning) (👨‍💻 27 · 🔀 140 · 📦 57 · 📋 45 - 11% open · ⏱️ 17.04.2021):

	```
	git clone https://github.com/tensorflow/neural-structured-learning
	```
- [PyPi](https://pypi.org/project/neural-structured-learning) (📥 6K / month):
	```
	pip install neural-structured-learning
	```
</details>
<details><summary><b><a href="https://github.com/taehoonlee/tensornets">TensorNets</a></b> (🥉19 ·  ⭐ 980) - High level network definitions with pre-trained weights in.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/taehoonlee/tensornets) (👨‍💻 6 · 🔀 190 · 📦 33 · 📋 56 - 25% open · ⏱️ 02.01.2021):

	```
	git clone https://github.com/taehoonlee/tensornets
	```
- [PyPi](https://pypi.org/project/tensornets) (📥 220 / month):
	```
	pip install tensornets
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/compression">TF Compression</a></b> (🥉18 ·  ⭐ 470) - Data compression in TensorFlow. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/compression) (👨‍💻 10 · 🔀 170 · ⏱️ 23.04.2021):

	```
	git clone https://github.com/tensorflow/compression
	```
- [PyPi](https://pypi.org/project/tensorflow-compression) (📥 990 / month):
	```
	pip install tensorflow-compression
	```
</details>
<details><summary><b><a href="https://github.com/geffy/tffm">tffm</a></b> (🥉17 ·  ⭐ 760 · 💤) - TensorFlow implementation of an arbitrary order Factorization Machine. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/geffy/tffm) (👨‍💻 10 · 🔀 180 · 📦 11 · 📋 37 - 45% open · ⏱️ 22.05.2020):

	```
	git clone https://github.com/geffy/tffm
	```
- [PyPi](https://pypi.org/project/tffm) (📥 2.3K / month):
	```
	pip install tffm
	```
</details>
<details><summary><b><a href="https://github.com/PAIR-code/saliency">Saliency</a></b> (🥉16 ·  ⭐ 660) - Framework-agnostic implementation for state-of-the-art saliency.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PAIR-code/saliency) (👨‍💻 14 · 🔀 140 · 📦 15 · 📋 22 - 54% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/PAIR-code/saliency
	```
- [PyPi](https://pypi.org/project/saliency) (📥 490 / month):
	```
	pip install saliency
	```
</details>
<br>

## Sklearn Utilities

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries that extend scikit-learn with additional capabilities._

<details><summary><b><a href="https://github.com/scikit-learn-contrib/imbalanced-learn">imbalanced-learn</a></b> (🥇31 ·  ⭐ 5.2K) - A Python Package to Tackle the Curse of Imbalanced.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/scikit-learn-contrib/imbalanced-learn) (👨‍💻 56 · 🔀 1K · 📦 5.1K · 📋 450 - 5% open · ⏱️ 25.04.2021):

	```
	git clone https://github.com/scikit-learn-contrib/imbalanced-learn
	```
- [PyPi](https://pypi.org/project/imbalanced-learn) (📥 1.4M / month):
	```
	pip install imbalanced-learn
	```
- [Conda](https://anaconda.org/conda-forge/imbalanced-learn) (📥 120K · ⏱️ 18.02.2021):
	```
	conda install -c conda-forge imbalanced-learn
	```
</details>
<details><summary><b><a href="https://github.com/rasbt/mlxtend">MLxtend</a></b> (🥇28 ·  ⭐ 3.4K) - A library of extension and helper modules for Python's data.. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rasbt/mlxtend) (👨‍💻 83 · 🔀 690 · 📦 3K · 📋 370 - 22% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/rasbt/mlxtend
	```
- [PyPi](https://pypi.org/project/mlxtend) (📥 320K / month):
	```
	pip install mlxtend
	```
- [Conda](https://anaconda.org/conda-forge/mlxtend) (📥 160K · ⏱️ 26.11.2020):
	```
	conda install -c conda-forge mlxtend
	```
</details>
<details><summary><b><a href="https://github.com/iskandr/fancyimpute">fancyimpute</a></b> (🥈25 ·  ⭐ 960) - Multivariate imputation and matrix completion algorithms.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/iskandr/fancyimpute) (👨‍💻 11 · 🔀 150 · 📦 900 · 📋 110 - 2% open · ⏱️ 25.01.2021):

	```
	git clone https://github.com/iskandr/fancyimpute
	```
- [PyPi](https://pypi.org/project/fancyimpute) (📥 16K / month):
	```
	pip install fancyimpute
	```
</details>
<details><summary><b><a href="https://github.com/guofei9987/scikit-opt">scikit-opt</a></b> (🥈23 ·  ⭐ 2.2K) - Genetic Algorithm, Particle Swarm Optimization, Simulated.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/guofei9987/scikit-opt) (👨‍💻 10 · 🔀 500 · 📦 30 · 📋 98 - 23% open · ⏱️ 03.04.2021):

	```
	git clone https://github.com/guofei9987/scikit-opt
	```
- [PyPi](https://pypi.org/project/scikit-opt) (📥 1.7K / month):
	```
	pip install scikit-opt
	```
</details>
<details><summary><b><a href="https://github.com/scikit-learn-contrib/category_encoders">category_encoders</a></b> (🥈23 ·  ⭐ 1.6K · 💤) - A library of sklearn compatible categorical variable.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/scikit-learn-contrib/category_encoders) (👨‍💻 37 · 🔀 300 · 📋 200 - 33% open · ⏱️ 31.07.2020):

	```
	git clone https://github.com/scikit-learn-contrib/category_encoders
	```
- [PyPi](https://pypi.org/project/category_encoders) (📥 340K / month):
	```
	pip install category_encoders
	```
- [Conda](https://anaconda.org/conda-forge/category_encoders) (📥 100K · ⏱️ 29.04.2020):
	```
	conda install -c conda-forge category_encoders
	```
</details>
<details><summary><b><a href="https://github.com/scikit-multilearn/scikit-multilearn">scikit-multilearn</a></b> (🥈23 ·  ⭐ 660 · 💀) - A scikit-learn based module for multi-label et. al... <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/scikit-multilearn/scikit-multilearn) (👨‍💻 15 · 🔀 120 · 📦 410 · 📋 160 - 41% open · ⏱️ 21.05.2019):

	```
	git clone https://github.com/scikit-multilearn/scikit-multilearn
	```
- [PyPi](https://pypi.org/project/scikit-multilearn) (📥 75K / month):
	```
	pip install scikit-multilearn
	```
</details>
<details><summary><b><a href="https://github.com/yzhao062/combo">combo</a></b> (🥈21 ·  ⭐ 490) - (AAAI' 20) A Python Toolbox for Machine Learning Model.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code> <code>xgboost</code></summary>

- [GitHub](https://github.com/yzhao062/combo) (🔀 84 · 📦 320 · 📋 12 - 75% open · ⏱️ 15.03.2021):

	```
	git clone https://github.com/yzhao062/combo
	```
- [PyPi](https://pypi.org/project/combo) (📥 28K / month):
	```
	pip install combo
	```
</details>
<details><summary><b><a href="https://github.com/scikit-learn-contrib/lightning">sklearn-contrib-lightning</a></b> (🥉20 ·  ⭐ 1.4K) - Large-scale linear classification, regression and.. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/scikit-learn-contrib/lightning) (👨‍💻 17 · 🔀 170 · 📦 82 · 📋 79 - 54% open · ⏱️ 14.03.2021):

	```
	git clone https://github.com/scikit-learn-contrib/lightning
	```
- [PyPi](https://pypi.org/project/sklearn-contrib-lightning) (📥 510 / month):
	```
	pip install sklearn-contrib-lightning
	```
- [Conda](https://anaconda.org/conda-forge/sklearn-contrib-lightning) (📥 140K · ⏱️ 20.12.2020):
	```
	conda install -c conda-forge sklearn-contrib-lightning
	```
</details>
<details><summary><b><a href="https://github.com/koaning/scikit-lego">scikit-lego</a></b> (🥉20 ·  ⭐ 490) - Extra blocks for scikit-learn pipelines. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/koaning/scikit-lego) (👨‍💻 45 · 🔀 71 · 📦 21 · 📋 220 - 10% open · ⏱️ 21.04.2021):

	```
	git clone https://github.com/koaning/scikit-lego
	```
- [PyPi](https://pypi.org/project/scikit-lego) (📥 3.2K / month):
	```
	pip install scikit-lego
	```
- [Conda](https://anaconda.org/conda-forge/scikit-lego) (📥 10K · ⏱️ 02.11.2020):
	```
	conda install -c conda-forge scikit-lego
	```
</details>
<details><summary><b><a href="https://github.com/TeamHG-Memex/sklearn-crfsuite">sklearn-crfsuite</a></b> (🥉20 ·  ⭐ 370 · 💀) - scikit-learn inspired API for CRFsuite. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/TeamHG-Memex/sklearn-crfsuite) (👨‍💻 6 · 🔀 160 · 📦 2.7K · 📋 47 - 53% open · ⏱️ 05.12.2019):

	```
	git clone https://github.com/TeamHG-Memex/sklearn-crfsuite
	```
- [PyPi](https://pypi.org/project/sklearn-crfsuite) (📥 100K / month):
	```
	pip install sklearn-crfsuite
	```
</details>
<details><summary><b><a href="https://github.com/trent-b/iterative-stratification">iterative-stratification</a></b> (🥉19 ·  ⭐ 550 · 💤) - scikit-learn cross validators for iterative.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/trent-b/iterative-stratification) (👨‍💻 4 · 🔀 49 · 📦 130 · 📋 13 - 15% open · ⏱️ 12.09.2020):

	```
	git clone https://github.com/trent-b/iterative-stratification
	```
- [PyPi](https://pypi.org/project/iterative-stratification) (📥 7.2K / month):
	```
	pip install iterative-stratification
	```
</details>
<details><summary><b><a href="https://github.com/scikit-learn-contrib/skope-rules">skope-rules</a></b> (🥉18 ·  ⭐ 370) - machine learning with logical rules in Python. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/scikit-learn-contrib/skope-rules) (👨‍💻 18 · 🔀 62 · 📦 31 · 📋 26 - 80% open · ⏱️ 23.10.2020):

	```
	git clone https://github.com/scikit-learn-contrib/skope-rules
	```
- [PyPi](https://pypi.org/project/skope-rules) (📥 20K / month):
	```
	pip install skope-rules
	```
</details>
<details><summary><b><a href="https://github.com/scikit-learn-contrib/DESlib">DESlib</a></b> (🥉18 ·  ⭐ 330) - A Python library for dynamic classifier and ensemble selection. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/scikit-learn-contrib/DESlib) (👨‍💻 13 · 🔀 52 · 📦 17 · 📋 140 - 6% open · ⏱️ 09.04.2021):

	```
	git clone https://github.com/scikit-learn-contrib/DESlib
	```
- [PyPi](https://pypi.org/project/deslib) (📥 1.1K / month):
	```
	pip install deslib
	```
</details>
<details><summary><b><a href="https://github.com/mathurinm/celer">celer</a></b> (🥉17 ·  ⭐ 110) - Fast solver for L1-type problems: Lasso, sparse Logisitic regression,.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/mathurinm/celer) (👨‍💻 9 · 🔀 22 · 📦 4 · 📋 66 - 22% open · ⏱️ 16.04.2021):

	```
	git clone https://github.com/mathurinm/celer
	```
- [PyPi](https://pypi.org/project/celer) (📥 170 / month):
	```
	pip install celer
	```
</details>
<details><summary><b><a href="https://github.com/scikit-tda/scikit-tda">scikit-tda</a></b> (🥉16 ·  ⭐ 280) - Topological Data Analysis for Python. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/scikit-tda/scikit-tda) (👨‍💻 2 · 🔀 31 · 📦 20 · 📋 15 - 73% open · ⏱️ 09.01.2021):

	```
	git clone https://github.com/scikit-tda/scikit-tda
	```
- [PyPi](https://pypi.org/project/scikit-tda) (📥 4.5K / month):
	```
	pip install scikit-tda
	```
</details>
<details><summary><b><a href="https://github.com/skggm/skggm">skggm</a></b> (🥉16 ·  ⭐ 180) - Scikit-learn compatible estimation of general graphical models. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/skggm/skggm) (👨‍💻 5 · 🔀 31 · 📦 6 · 📋 75 - 37% open · ⏱️ 24.12.2020):

	```
	git clone https://github.com/skggm/skggm
	```
- [PyPi](https://pypi.org/project/skggm) (📥 130 / month):
	```
	pip install skggm
	```
</details>
<details><summary><b><a href="https://github.com/amueller/dabl">dabl</a></b> (🥉14 ·  ⭐ 72 · 💤) - Data Analysis Baseline Library. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/amueller/dabl) (👨‍💻 18 · 🔀 7 · ⏱️ 08.07.2020):

	```
	git clone https://github.com/amueller/dabl
	```
- [PyPi](https://pypi.org/project/dabl) (📥 2.8K / month):
	```
	pip install dabl
	```
</details>
<br>

## Pytorch Utilities

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries that extend Pytorch with additional capabilities._

<details><summary><b><a href="https://github.com/Cadene/pretrained-models.pytorch">pretrainedmodels</a></b> (🥇25 ·  ⭐ 7.9K · 💤) - Pretrained ConvNets for pytorch: NASNet, ResNeXt,.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/Cadene/pretrained-models.pytorch) (👨‍💻 22 · 🔀 1.6K · 📦 980 · 📋 160 - 46% open · ⏱️ 16.04.2020):

	```
	git clone https://github.com/Cadene/pretrained-models.pytorch
	```
- [PyPi](https://pypi.org/project/pretrainedmodels) (📥 56K / month):
	```
	pip install pretrainedmodels
	```
</details>
<details><summary><b><a href="https://github.com/KevinMusgrave/pytorch-metric-learning">PML</a></b> (🥇25 ·  ⭐ 3.1K) - The easiest way to use deep metric learning in your application. Modular,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/KevinMusgrave/pytorch-metric-learning) (👨‍💻 15 · 🔀 400 · 📦 74 · 📋 250 - 18% open · ⏱️ 03.04.2021):

	```
	git clone https://github.com/KevinMusgrave/pytorch-metric-learning
	```
- [PyPi](https://pypi.org/project/pytorch-metric-learning) (📥 16K / month):
	```
	pip install pytorch-metric-learning
	```
- [Conda](https://anaconda.org/metric-learning/pytorch-metric-learning) (📥 2K · ⏱️ 03.04.2021):
	```
	conda install -c metric-learning pytorch-metric-learning
	```
</details>
<details><summary><b><a href="https://github.com/jettify/pytorch-optimizer">pytorch-optimizer</a></b> (🥇25 ·  ⭐ 1.8K) - torch-optimizer -- collection of optimizers for.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/jettify/pytorch-optimizer) (👨‍💻 19 · 🔀 170 · 📦 180 · 📋 31 - 19% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/jettify/pytorch-optimizer
	```
- [PyPi](https://pypi.org/project/torch_optimizer) (📥 32K / month):
	```
	pip install torch_optimizer
	```
</details>
<details><summary><b><a href="https://github.com/sksq96/pytorch-summary">pytorch-summary</a></b> (🥈24 ·  ⭐ 3.1K · 💤) - Model summary in PyTorch similar to `model.summary()`.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/sksq96/pytorch-summary) (👨‍💻 11 · 🔀 360 · 📦 2.4K · 📋 120 - 70% open · ⏱️ 07.08.2020):

	```
	git clone https://github.com/sksq96/pytorch-summary
	```
- [PyPi](https://pypi.org/project/torchsummary) (📥 70K / month):
	```
	pip install torchsummary
	```
</details>
<details><summary><b><a href="https://github.com/asappresearch/sru">SRU</a></b> (🥈24 ·  ⭐ 1.9K) - Training RNNs as Fast as CNNs (https://arxiv.org/abs/1709.02755). <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/asappresearch/sru) (👨‍💻 21 · 🔀 280 · 📦 15 · 📋 110 - 42% open · ⏱️ 19.03.2021):

	```
	git clone https://github.com/asappresearch/sru
	```
- [PyPi](https://pypi.org/project/sru) (📥 2.9K / month):
	```
	pip install sru
	```
</details>
<details><summary><b><a href="https://github.com/lukemelas/EfficientNet-PyTorch">EfficientNet-PyTorch</a></b> (🥈22 ·  ⭐ 5.9K) - A PyTorch implementation of EfficientNet and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/lukemelas/EfficientNet-PyTorch) (👨‍💻 24 · 🔀 1.1K · 📥 460K · 📋 240 - 44% open · ⏱️ 15.04.2021):

	```
	git clone https://github.com/lukemelas/EfficientNet-PyTorch
	```
- [PyPi](https://pypi.org/project/efficientnet-pytorch) (📥 72K / month):
	```
	pip install efficientnet-pytorch
	```
</details>
<details><summary><b><a href="https://github.com/rtqichen/torchdiffeq">torchdiffeq</a></b> (🥈21 ·  ⭐ 3.5K) - Differentiable ODE solvers with full GPU support and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rtqichen/torchdiffeq) (👨‍💻 19 · 🔀 580 · 📦 90 · 📋 130 - 14% open · ⏱️ 23.03.2021):

	```
	git clone https://github.com/rtqichen/torchdiffeq
	```
- [PyPi](https://pypi.org/project/torchdiffeq) (📥 3.4K / month):
	```
	pip install torchdiffeq
	```
</details>
<details><summary><b><a href="https://github.com/lucidrains/reformer-pytorch">reformer-pytorch</a></b> (🥈21 ·  ⭐ 1.5K) - Reformer, the efficient Transformer, in Pytorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/lucidrains/reformer-pytorch) (👨‍💻 10 · 🔀 190 · 📋 110 - 7% open · ⏱️ 21.04.2021):

	```
	git clone https://github.com/lucidrains/reformer-pytorch
	```
- [PyPi](https://pypi.org/project/reformer-pytorch) (📥 2.2K / month):
	```
	pip install reformer-pytorch
	```
</details>
<details><summary><b><a href="https://github.com/dreamquark-ai/tabnet">TabNet</a></b> (🥈21 ·  ⭐ 970) - PyTorch implementation of TabNet paper :.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/dreamquark-ai/tabnet) (👨‍💻 18 · 🔀 190 · 📋 130 - 18% open · ⏱️ 01.03.2021):

	```
	git clone https://github.com/dreamquark-ai/tabnet
	```
- [PyPi](https://pypi.org/project/pytorch-tabnet) (📥 11K / month):
	```
	pip install pytorch-tabnet
	```
</details>
<details><summary><b><a href="https://github.com/rwightman/gen-efficientnet-pytorch">EfficientNets</a></b> (🥈20 ·  ⭐ 1.3K) - Pretrained EfficientNet, EfficientNet-Lite, MixNet,.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rwightman/gen-efficientnet-pytorch) (👨‍💻 5 · 🔀 180 · 📦 48 · ⏱️ 30.11.2020):

	```
	git clone https://github.com/rwightman/gen-efficientnet-pytorch
	```
- [PyPi](https://pypi.org/project/geffnet) (📥 6.1K / month):
	```
	pip install geffnet
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/higher">Higher</a></b> (🥈20 ·  ⭐ 1.1K) - higher is a pytorch library allowing users to obtain higher.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/higher) (👨‍💻 8 · 🔀 79 · 📦 48 · 📋 80 - 40% open · ⏱️ 02.03.2021):

	```
	git clone https://github.com/facebookresearch/higher
	```
- [PyPi](https://pypi.org/project/higher) (📥 23K / month):
	```
	pip install higher
	```
</details>
<details><summary><b><a href="https://github.com/BloodAxe/pytorch-toolbelt">Pytorch Toolbelt</a></b> (🥈20 ·  ⭐ 990) - PyTorch extensions for fast R&D prototyping and Kaggle.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/BloodAxe/pytorch-toolbelt) (👨‍💻 5 · 🔀 73 · 📋 18 - 11% open · ⏱️ 17.04.2021):

	```
	git clone https://github.com/BloodAxe/pytorch-toolbelt
	```
- [PyPi](https://pypi.org/project/pytorch_toolbelt) (📥 12K / month):
	```
	pip install pytorch_toolbelt
	```
</details>
<details><summary><b><a href="https://github.com/rusty1s/pytorch_scatter">torch-scatter</a></b> (🥈20 ·  ⭐ 650) - PyTorch Extension Library of Optimized Scatter Operations. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rusty1s/pytorch_scatter) (👨‍💻 15 · 🔀 76 · 📋 190 - 34% open · ⏱️ 25.03.2021):

	```
	git clone https://github.com/rusty1s/pytorch_scatter
	```
- [PyPi](https://pypi.org/project/torch-scatter) (📥 22K / month):
	```
	pip install torch-scatter
	```
</details>
<details><summary><b><a href="https://github.com/GRAAL-Research/poutyne">Poutyne</a></b> (🥈20 ·  ⭐ 470) - A simplified framework and utilities for PyTorch. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/GRAAL-Research/poutyne) (👨‍💻 16 · 🔀 50 · 📦 59 · 📋 43 - 13% open · ⏱️ 15.04.2021):

	```
	git clone https://github.com/GRAAL-Research/poutyne
	```
- [PyPi](https://pypi.org/project/poutyne) (📥 1.5K / month):
	```
	pip install poutyne
	```
</details>
<details><summary><b><a href="https://github.com/rusty1s/pytorch_sparse">PyTorch Sparse</a></b> (🥈20 ·  ⭐ 400) - PyTorch Extension Library of Optimized Autograd Sparse.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rusty1s/pytorch_sparse) (👨‍💻 15 · 🔀 52 · 📋 100 - 42% open · ⏱️ 25.04.2021):

	```
	git clone https://github.com/rusty1s/pytorch_sparse
	```
- [PyPi](https://pypi.org/project/torch-sparse) (📥 14K / month):
	```
	pip install torch-sparse
	```
</details>
<details><summary><b><a href="https://github.com/Luolc/AdaBound">AdaBound</a></b> (🥉19 ·  ⭐ 2.8K · 💀) - An optimizer that trains as fast as Adam and as good as SGD. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/Luolc/AdaBound) (👨‍💻 2 · 🔀 320 · 📦 110 · 📋 23 - 69% open · ⏱️ 06.03.2019):

	```
	git clone https://github.com/Luolc/AdaBound
	```
- [PyPi](https://pypi.org/project/adabound) (📥 1.2K / month):
	```
	pip install adabound
	```
</details>
<details><summary><b><a href="https://github.com/lucidrains/lambda-networks">Lambda Networks</a></b> (🥉19 ·  ⭐ 1.4K · 🐣) - Implementation of LambdaNetworks, a new approach to.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/lucidrains/lambda-networks) (👨‍💻 3 · 🔀 150 · 📦 3 · 📋 27 - 44% open · ⏱️ 18.11.2020):

	```
	git clone https://github.com/lucidrains/lambda-networks
	```
- [PyPi](https://pypi.org/project/lambda-networks) (📥 2.3K / month):
	```
	pip install lambda-networks
	```
</details>
<details><summary><b><a href="https://github.com/tristandeleu/pytorch-meta">Torchmeta</a></b> (🥉19 ·  ⭐ 1.3K) - A collection of extensions and data-loaders for few-shot learning.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tristandeleu/pytorch-meta) (👨‍💻 10 · 🔀 150 · 📦 36 · 📋 100 - 25% open · ⏱️ 19.03.2021):

	```
	git clone https://github.com/tristandeleu/pytorch-meta
	```
- [PyPi](https://pypi.org/project/torchmeta) (📥 1.2K / month):
	```
	pip install torchmeta
	```
</details>
<details><summary><b><a href="https://github.com/lucidrains/performer-pytorch">Performer Pytorch</a></b> (🥉19 ·  ⭐ 590 · 🐣) - An implementation of Performer, a linear attention-.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/lucidrains/performer-pytorch) (👨‍💻 4 · 🔀 74 · 📦 17 · 📋 58 - 34% open · ⏱️ 21.04.2021):

	```
	git clone https://github.com/lucidrains/performer-pytorch
	```
- [PyPi](https://pypi.org/project/performer-pytorch) (📥 3.2K / month):
	```
	pip install performer-pytorch
	```
</details>
<details><summary><b><a href="https://github.com/adobe/antialiased-cnns">Antialiased CNNs</a></b> (🥉18 ·  ⭐ 1.4K) - pip install antialiased-cnns to improve stability and.. <code><a href="https://tldrlegal.com/search?q=CC%20BY-NC-SA%204.0">❗️CC BY-NC-SA 4.0</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/adobe/antialiased-cnns) (👨‍💻 6 · 🔀 180 · 📋 39 - 20% open · ⏱️ 22.10.2020):

	```
	git clone https://github.com/adobe/antialiased-cnns
	```
- [PyPi](https://pypi.org/project/antialiased-cnns) (📥 2.1K / month):
	```
	pip install antialiased-cnns
	```
</details>
<details><summary><b><a href="https://github.com/parrt/tensor-sensor">Tensor Sensor</a></b> (🥉17 ·  ⭐ 550) - The goal of this library is to generate more helpful.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/parrt/tensor-sensor) (👨‍💻 2 · 🔀 26 · 📦 2 · 📋 17 - 29% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/parrt/tensor-sensor
	```
- [PyPi](https://pypi.org/project/tensor-sensor) (📥 390 / month):
	```
	pip install tensor-sensor
	```
</details>
<details><summary><b><a href="https://github.com/geohot/tinygrad">tinygrad</a></b> (🥉16 ·  ⭐ 4.3K · 🐣) - You like pytorch? You like micrograd? You love tinygrad!. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/geohot/tinygrad) (👨‍💻 43 · 🔀 470 · 📦 1 · 📋 76 - 17% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/geohot/tinygrad
	```
</details>
<details><summary><b><a href="https://github.com/google-research/torchsde">torchsde</a></b> (🥉16 ·  ⭐ 700) - Differentiable SDE solvers with GPU support and efficient.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/google-research/torchsde) (👨‍💻 4 · 🔀 63 · 📋 36 - 13% open · ⏱️ 10.04.2021):

	```
	git clone https://github.com/google-research/torchsde
	```
</details>
<details><summary><b><a href="https://github.com/harvardnlp/pytorch-struct">Torch-Struct</a></b> (🥉15 ·  ⭐ 920) - Fast, general, and tested differentiable structured prediction.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/harvardnlp/pytorch-struct) (👨‍💻 13 · 🔀 71 · 📋 39 - 38% open · ⏱️ 14.02.2021):

	```
	git clone https://github.com/harvardnlp/pytorch-struct
	```
</details>
<details><summary><b><a href="https://github.com/achaiah/pywick">Pywick</a></b> (🥉15 ·  ⭐ 320) - High-level batteries-included neural network training library.. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/achaiah/pywick) (👨‍💻 4 · 🔀 35 · 📦 3 · 📋 12 - 25% open · ⏱️ 01.03.2021):

	```
	git clone https://github.com/achaiah/pywick
	```
- [PyPi](https://pypi.org/project/pywick) (📥 320 / month):
	```
	pip install pywick
	```
</details>
<details><summary><b><a href="https://github.com/karpathy/micrograd">micrograd</a></b> (🥉12 ·  ⭐ 1.6K · 💤) - A tiny scalar-valued autograd engine and a neural net library.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/karpathy/micrograd) (👨‍💻 2 · 🔀 120 · 📦 1 · 📋 5 - 40% open · ⏱️ 18.04.2020):

	```
	git clone https://github.com/karpathy/micrograd
	```
- [PyPi](https://pypi.org/project/micrograd) (📥 29 / month):
	```
	pip install micrograd
	```
</details>
<details><summary><b><a href="https://github.com/abhi1thakur/tez">Tez</a></b> (🥉12 ·  ⭐ 600 · 🐣) - Tez is a super-simple and lightweight Trainer for PyTorch. It.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/abhi1thakur/tez) (👨‍💻 2 · 🔀 78 · 📦 6 · 📋 19 - 63% open · ⏱️ 06.03.2021):

	```
	git clone https://github.com/abhishekkrthakur/tez
	```
- [PyPi](https://pypi.org/project/tez) (📥 720 / month):
	```
	pip install tez
	```
</details>
<br>

## Database Clients

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for connecting to, operating, and querying databases._

🔗&nbsp;<b><a href="https://github.com/HanXinzi2020/awesome-python-resources#数据库">Python DB Clients</a></b>  - Collection of database clients for python.

<br>

## Chinese NLP

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/fxsjy/jieba">jieba</a></b> (🥇30 ·  ⭐ 26K · 💀) - Chinese Words Segementation Utilities. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/fxsjy/jieba) (👨‍💻 48 · 🔀 6K · 📦 9.9K · 📋 760 - 73% open · ⏱️ 15.02.2020):

	```
	git clone https://github.com/fxsjy/jieba
	```
- [PyPi](https://pypi.org/project/jieba) (📥 420K / month):
	```
	pip install jieba
	```
- [Conda](https://anaconda.org/conda-forge/jieba) (📥 75K · ⏱️ 25.03.2020):
	```
	conda install -c conda-forge jieba
	```
</details>
<details><summary><b><a href="https://github.com/isnowfy/snownlp">snownlp</a></b> (🥉22 ·  ⭐ 5.4K · 💀) - Python library for processing Chinese text. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/isnowfy/snownlp) (👨‍💻 8 · 🔀 1.3K · 📦 570 · 📋 99 - 34% open · ⏱️ 19.01.2020):

	```
	git clone https://github.com/isnowfy/snownlp
	```
- [PyPi](https://pypi.org/project/snownlp) (📥 15K / month):
	```
	pip install snownlp
	```
</details>
<br>

## Others

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/scipy/scipy">scipy</a></b> (🥇41 ·  ⭐ 8.2K) - Ecosystem of open-source software for mathematics, science, and engineering. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/scipy/scipy) (👨‍💻 1.2K · 🔀 3.6K · 📥 310K · 📦 330K · 📋 7.2K - 18% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/scipy/scipy
	```
- [PyPi](https://pypi.org/project/scipy) (📥 29M / month):
	```
	pip install scipy
	```
- [Conda](https://anaconda.org/conda-forge/scipy) (📥 14M · ⏱️ 27.04.2021):
	```
	conda install -c conda-forge scipy
	```
</details>
<details><summary><b><a href="https://github.com/sympy/sympy">SymPy</a></b> (🥇33 ·  ⭐ 8K) - A computer algebra system written in pure Python. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/sympy/sympy) (👨‍💻 1.1K · 🔀 3.3K · 📥 420K · 📦 31K · 📋 11K - 33% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/sympy/sympy
	```
- [PyPi](https://pypi.org/project/sympy) (📥 1M / month):
	```
	pip install sympy
	```
- [Conda](https://anaconda.org/conda-forge/sympy) (📥 1.4M · ⏱️ 10.04.2021):
	```
	conda install -c conda-forge sympy
	```
</details>
<details><summary><b><a href="https://github.com/HIPS/autograd">Autograd</a></b> (🥇29 ·  ⭐ 5.2K) - Efficiently computes derivatives of numpy code. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/HIPS/autograd) (👨‍💻 51 · 🔀 720 · 📦 1.8K · 📋 360 - 39% open · ⏱️ 03.03.2021):

	```
	git clone https://github.com/HIPS/autograd
	```
- [PyPi](https://pypi.org/project/autograd) (📥 1.2M / month):
	```
	pip install autograd
	```
- [Conda](https://anaconda.org/conda-forge/autograd) (📥 170K · ⏱️ 25.07.2019):
	```
	conda install -c conda-forge autograd
	```
</details>
<details><summary><b><a href="https://github.com/yzhao062/pyod">PyOD</a></b> (🥇28 ·  ⭐ 4.4K) - (JMLR'19) A Python Toolbox for Scalable Outlier Detection (Anomaly.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/yzhao062/pyod) (👨‍💻 23 · 🔀 890 · 📦 590 · 📋 190 - 54% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/yzhao062/pyod
	```
- [PyPi](https://pypi.org/project/pyod) (📥 150K / month):
	```
	pip install pyod
	```
</details>
<details><summary><b><a href="https://github.com/streamlit/streamlit">Streamlit</a></b> (🥈27 ·  ⭐ 14K) - Streamlit The fastest way to build data apps in Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/streamlit/streamlit) (👨‍💻 100 · 🔀 1.2K · 📦 75 · 📋 1.7K - 29% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/streamlit/streamlit
	```
- [PyPi](https://pypi.org/project/streamlit) (📥 250K / month):
	```
	pip install streamlit
	```
</details>
<details><summary><b><a href="https://github.com/simonw/datasette">Datasette</a></b> (🥈27 ·  ⭐ 5K) - An open source multi-tool for exploring and publishing data. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/simonw/datasette) (👨‍💻 49 · 🔀 280 · 📥 29 · 📦 410 · 📋 1K - 24% open · ⏱️ 24.04.2021):

	```
	git clone https://github.com/simonw/datasette
	```
- [PyPi](https://pypi.org/project/datasette) (📥 19K / month):
	```
	pip install datasette
	```
</details>
<details><summary><b><a href="https://github.com/scikit-learn-contrib/hdbscan">hdbscan</a></b> (🥈27 ·  ⭐ 1.9K) - A high performance implementation of HDBSCAN clustering. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/scikit-learn-contrib/hdbscan) (👨‍💻 69 · 🔀 320 · 📦 820 · 📋 370 - 60% open · ⏱️ 07.04.2021):

	```
	git clone https://github.com/scikit-learn-contrib/hdbscan
	```
- [PyPi](https://pypi.org/project/hdbscan) (📥 210K / month):
	```
	pip install hdbscan
	```
- [Conda](https://anaconda.org/conda-forge/hdbscan) (📥 640K · ⏱️ 14.02.2021):
	```
	conda install -c conda-forge hdbscan
	```
</details>
<details><summary><b><a href="https://github.com/carla-simulator/carla">carla</a></b> (🥈26 ·  ⭐ 5.9K) - Open-source simulator for autonomous driving research. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/carla-simulator/carla) (👨‍💻 120 · 🔀 1.7K · 📦 64 · 📋 3.2K - 10% open · ⏱️ 21.04.2021):

	```
	git clone https://github.com/carla-simulator/carla
	```
- [PyPi](https://pypi.org/project/carla) (📥 920 / month):
	```
	pip install carla
	```
</details>
<details><summary><b><a href="https://github.com/deepchem/deepchem">DeepChem</a></b> (🥈26 ·  ⭐ 2.9K) - Democratizing Deep-Learning for Drug Discovery, Quantum Chemistry,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deepchem/deepchem) (👨‍💻 160 · 🔀 930 · 📦 38 · 📋 1.2K - 27% open · ⏱️ 21.04.2021):

	```
	git clone https://github.com/deepchem/deepchem
	```
- [PyPi](https://pypi.org/project/deepchem) (📥 5.7K / month):
	```
	pip install deepchem
	```
</details>
<details><summary><b><a href="https://github.com/wireservice/agate">agate</a></b> (🥈26 ·  ⭐ 1K) - A Python data analysis library that is optimized for humans instead of machines. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/wireservice/agate) (👨‍💻 47 · 🔀 130 · 📦 550 · 📋 630 - 7% open · ⏱️ 10.03.2021):

	```
	git clone https://github.com/wireservice/agate
	```
- [PyPi](https://pypi.org/project/agate) (📥 490K / month):
	```
	pip install agate
	```
- [Conda](https://anaconda.org/conda-forge/agate) (📥 63K · ⏱️ 19.08.2018):
	```
	conda install -c conda-forge agate
	```
</details>
<details><summary><b><a href="https://github.com/google/trax">Trax</a></b> (🥈25 ·  ⭐ 6.1K) - Trax Deep Learning with Clear Code and Speed. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google/trax) (👨‍💻 68 · 🔀 580 · 📦 26 · 📋 180 - 39% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/google/trax
	```
- [PyPi](https://pypi.org/project/trax) (📥 4.7K / month):
	```
	pip install trax
	```
</details>
<details><summary><b><a href="https://github.com/tableau/TabPy">TabPy</a></b> (🥈25 ·  ⭐ 1.1K) - Execute Python code on the fly and display results in Tableau visualizations:. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/tableau/TabPy) (👨‍💻 40 · 🔀 390 · 📦 57 · 📋 270 - 3% open · ⏱️ 04.02.2021):

	```
	git clone https://github.com/tableau/TabPy
	```
- [PyPi](https://pypi.org/project/tabpy) (📥 33K / month):
	```
	pip install tabpy
	```
</details>
<details><summary><b><a href="https://github.com/annoviko/pyclustering">pyclustering</a></b> (🥈25 ·  ⭐ 820) - pyclustring is a Python, C++ data mining library. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/annoviko/pyclustering) (👨‍💻 26 · 🔀 190 · 📥 320 · 📦 190 · 📋 630 - 7% open · ⏱️ 12.02.2021):

	```
	git clone https://github.com/annoviko/pyclustering
	```
- [PyPi](https://pypi.org/project/pyclustering) (📥 38K / month):
	```
	pip install pyclustering
	```
- [Conda](https://anaconda.org/conda-forge/pyclustering) (📥 20K · ⏱️ 25.01.2021):
	```
	conda install -c conda-forge pyclustering
	```
</details>
<details><summary><b><a href="https://github.com/explosion/cython-blis">Cython BLIS</a></b> (🥈25 ·  ⭐ 170) - Fast matrix-multiplication as a self-contained Python.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/explosion/cython-blis) (👨‍💻 9 · 🔀 25 · 📦 9.8K · 📋 21 - 23% open · ⏱️ 15.03.2021):

	```
	git clone https://github.com/explosion/cython-blis
	```
- [PyPi](https://pypi.org/project/blis) (📥 1.8M / month):
	```
	pip install blis
	```
- [Conda](https://anaconda.org/conda-forge/cython-blis) (📥 660K · ⏱️ 31.01.2021):
	```
	conda install -c conda-forge cython-blis
	```
</details>
<details><summary><b><a href="https://github.com/serge-sans-paille/pythran">Pythran</a></b> (🥉24 ·  ⭐ 1.5K) - Ahead of Time compiler for numeric kernels. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/serge-sans-paille/pythran) (👨‍💻 54 · 🔀 140 · 📦 52 · 📋 660 - 14% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/serge-sans-paille/pythran
	```
- [PyPi](https://pypi.org/project/pythran) (📥 12K / month):
	```
	pip install pythran
	```
- [Conda](https://anaconda.org/conda-forge/pythran) (📥 150K · ⏱️ 01.04.2021):
	```
	conda install -c conda-forge pythran
	```
</details>
<details><summary><b><a href="https://github.com/pyjanitor-devs/pyjanitor">pyjanitor</a></b> (🥉24 ·  ⭐ 660) - Clean APIs for data cleaning. Python implementation of R package Janitor. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pyjanitor-devs/pyjanitor) (👨‍💻 88 · 🔀 120 · 📦 94 · 📋 380 - 25% open · ⏱️ 20.04.2021):

	```
	git clone https://github.com/ericmjl/pyjanitor
	```
- [PyPi](https://pypi.org/project/pyjanitor) (📥 6.7K / month):
	```
	pip install pyjanitor
	```
- [Conda](https://anaconda.org/conda-forge/pyjanitor) (📥 87K · ⏱️ 25.03.2021):
	```
	conda install -c conda-forge pyjanitor
	```
</details>
<details><summary><b><a href="https://github.com/PaddlePaddle/PaddleHub">PaddleHub</a></b> (🥉23 ·  ⭐ 5K) - Awesome pre-trained models toolkit based on PaddlePaddle.300+.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PaddlePaddle/PaddleHub) (👨‍💻 37 · 🔀 1.1K · 📥 490 · 📦 170 · 📋 780 - 28% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/PaddlePaddle/PaddleHub
	```
- [PyPi](https://pypi.org/project/paddlehub) (📥 2.9K / month):
	```
	pip install paddlehub
	```
</details>
<details><summary><b><a href="https://github.com/uber/causalml">causalml</a></b> (🥉23 ·  ⭐ 1.9K) - Uplift modeling and causal inference with machine learning.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/uber/causalml) (👨‍💻 25 · 🔀 280 · 📦 18 · 📋 170 - 17% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/uber/causalml
	```
- [PyPi](https://pypi.org/project/causalml) (📥 19K / month):
	```
	pip install causalml
	```
</details>
<details><summary><b><a href="https://github.com/scikit-learn-contrib/metric-learn">metric-learn</a></b> (🥉23 ·  ⭐ 1.1K) - Metric learning algorithms in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/scikit-learn-contrib/metric-learn) (👨‍💻 19 · 🔀 210 · 📦 130 · 📋 160 - 30% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/scikit-learn-contrib/metric-learn
	```
- [PyPi](https://pypi.org/project/metric-learn) (📥 7.9K / month):
	```
	pip install metric-learn
	```
</details>
<details><summary><b><a href="https://github.com/ljvmiranda921/pyswarms">PySwarms</a></b> (🥉23 ·  ⭐ 770) - A research toolkit for particle swarm optimization in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ljvmiranda921/pyswarms) (👨‍💻 43 · 🔀 240 · 📦 100 · 📋 180 - 12% open · ⏱️ 02.04.2021):

	```
	git clone https://github.com/ljvmiranda921/pyswarms
	```
- [PyPi](https://pypi.org/project/pyswarms) (📥 6K / month):
	```
	pip install pyswarms
	```
</details>
<details><summary><b><a href="https://github.com/minrk/findspark">findspark</a></b> (🥉23 ·  ⭐ 400 · 💤) - Find pyspark to make it importable. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/minrk/findspark) (👨‍💻 14 · 🔀 68 · 📦 1.7K · 📋 18 - 55% open · ⏱️ 08.06.2020):

	```
	git clone https://github.com/minrk/findspark
	```
- [PyPi](https://pypi.org/project/findspark) (📥 1M / month):
	```
	pip install findspark
	```
- [Conda](https://anaconda.org/conda-forge/findspark) (📥 530K · ⏱️ 06.07.2018):
	```
	conda install -c conda-forge findspark
	```
</details>
<details><summary><b><a href="https://github.com/gradio-app/gradio">Gradio</a></b> (🥉21 ·  ⭐ 2.4K) - Wrap UIs around any model, share with anyone. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/gradio-app/gradio) (👨‍💻 16 · 🔀 150 · 📦 110 · 📋 97 - 8% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/gradio-app/gradio
	```
- [PyPi](https://pypi.org/project/gradio) (📥 4.8K / month):
	```
	pip install gradio
	```
</details>
<details><summary><b><a href="https://github.com/cgnorthcutt/cleanlab">cleanlab</a></b> (🥉21 ·  ⭐ 1.9K) - The standard package for machine learning with noisy labels and.. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/cgnorthcutt/cleanlab) (👨‍💻 6 · 🔀 180 · 📦 11 · 📋 59 - 30% open · ⏱️ 20.04.2021):

	```
	git clone https://github.com/cgnorthcutt/cleanlab
	```
- [PyPi](https://pypi.org/project/cleanlab) (📥 4.4K / month):
	```
	pip install cleanlab
	```
</details>
<details><summary><b><a href="https://github.com/inducer/pyopencl">pyopencl</a></b> (🥉20 ·  ⭐ 800) - OpenCL integration for Python, plus shiny features. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/inducer/pyopencl) (👨‍💻 86 · 🔀 210 · 📦 500 · 📋 270 - 20% open · ⏱️ 23.04.2021):

	```
	git clone https://github.com/inducer/pyopencl
	```
- [PyPi](https://pypi.org/project/pyopencl) (📥 21K / month):
	```
	pip install pyopencl
	```
- [Conda](https://anaconda.org/conda-forge/pyopencl) (📥 390K · ⏱️ 05.04.2021):
	```
	conda install -c conda-forge pyopencl
	```
</details>
<details><summary><b><a href="https://github.com/solegalli/feature_engine">Feature Engine</a></b> (🥉20 ·  ⭐ 510) - Feature engineering package with sklearn like functionality. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/solegalli/feature_engine) (👨‍💻 22 · 🔀 140 · 📋 110 - 23% open · ⏱️ 25.04.2021):

	```
	git clone https://github.com/solegalli/feature_engine
	```
- [PyPi](https://pypi.org/project/feature_engine) (📥 22K / month):
	```
	pip install feature_engine
	```
- [Conda](https://anaconda.org/conda-forge/feature_engine) (📥 2.7K · ⏱️ 25.01.2021):
	```
	conda install -c conda-forge feature_engine
	```
</details>
<details><summary><b><a href="https://github.com/rasbt/biopandas">BioPandas</a></b> (🥉20 ·  ⭐ 340) - Working with molecular structures in pandas DataFrames. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rasbt/biopandas) (👨‍💻 7 · 🔀 78 · 📦 53 · 📋 36 - 41% open · ⏱️ 07.04.2021):

	```
	git clone https://github.com/rasbt/biopandas
	```
- [PyPi](https://pypi.org/project/biopandas) (📥 950 / month):
	```
	pip install biopandas
	```
- [Conda](https://anaconda.org/conda-forge/biopandas) (📥 73K · ⏱️ 08.08.2020):
	```
	conda install -c conda-forge biopandas
	```
</details>
<details><summary><b><a href="https://github.com/airbnb/streamalert">StreamAlert</a></b> (🥉19 ·  ⭐ 2.5K) - StreamAlert is a serverless, realtime data analysis framework.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/airbnb/streamalert) (👨‍💻 31 · 🔀 290 · 📋 340 - 26% open · ⏱️ 10.02.2021):

	```
	git clone https://github.com/airbnb/streamalert
	```
</details>
<details><summary><b><a href="https://github.com/MaxHalford/prince">Prince</a></b> (🥉19 ·  ⭐ 630) - Python factor analysis library (PCA, CA, MCA, MFA, FAMD). <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/MaxHalford/prince) (👨‍💻 8 · 🔀 120 · 📦 110 · 📋 93 - 31% open · ⏱️ 11.01.2021):

	```
	git clone https://github.com/MaxHalford/prince
	```
- [PyPi](https://pypi.org/project/prince) (📥 7.8K / month):
	```
	pip install prince
	```
</details>
<details><summary><b><a href="https://github.com/yzhao062/SUOD">SUOD</a></b> (🥉19 ·  ⭐ 260) - (MLSys' 21) An Acceleration System for Large-scare Unsupervised.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/yzhao062/SUOD) (🔀 30 · 📦 310 · 📋 5 - 60% open · ⏱️ 19.01.2021):

	```
	git clone https://github.com/yzhao062/SUOD
	```
- [PyPi](https://pypi.org/project/suod) (📥 19K / month):
	```
	pip install suod
	```
</details>
<details><summary><b><a href="https://github.com/online-ml/river">River</a></b> (🥉18 ·  ⭐ 1.6K) - Online machine learning in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/online-ml/river) (👨‍💻 63 · 🔀 200 · 📦 9 · 📋 290 - 7% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/online-ml/river
	```
</details>
<details><summary><b><a href="https://github.com/trevorstephens/gplearn">gplearn</a></b> (🥉18 ·  ⭐ 930 · 💀) - Genetic Programming in Python, with a scikit-learn inspired API. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/trevorstephens/gplearn) (👨‍💻 9 · 🔀 160 · 📦 150 · 📋 150 - 22% open · ⏱️ 15.02.2020):

	```
	git clone https://github.com/trevorstephens/gplearn
	```
- [PyPi](https://pypi.org/project/gplearn) (📥 1.9K / month):
	```
	pip install gplearn
	```
</details>
<details><summary><b><a href="https://github.com/eltonlaw/impyute">impyute</a></b> (🥉18 ·  ⭐ 280 · 💀) - Data imputations library to preprocess datasets with missing data. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/eltonlaw/impyute) (👨‍💻 9 · 🔀 41 · 📦 89 · 📋 62 - 41% open · ⏱️ 05.10.2019):

	```
	git clone https://github.com/eltonlaw/impyute
	```
- [PyPi](https://pypi.org/project/impyute) (📥 2.8K / month):
	```
	pip install impyute
	```
</details>
<details><summary><b><a href="https://github.com/astroML/astroML">AstroML</a></b> (🥉17 ·  ⭐ 740) - Machine learning, statistics, and data mining for astronomy and.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/astroML/astroML) (👨‍💻 30 · 🔀 260 · 📋 130 - 36% open · ⏱️ 07.04.2021):

	```
	git clone https://github.com/astroML/astroML
	```
- [PyPi](https://pypi.org/project/astroML) (📥 1.5K / month):
	```
	pip install astroML
	```
- [Conda](https://anaconda.org/conda-forge/astroml) (📥 23K · ⏱️ 16.02.2020):
	```
	conda install -c conda-forge astroml
	```
</details>

---

## 相关资源

- [**Python资源汇集列表**](https://github.com/HanXinzi-AI/awesome-python-resources): 周更新的各种应用方向与主题的资源汇集列表
- [**python机器学习资源大全**](https://github.com/HanXinzi-AI/awesome-python-machine-learning-resources): 周更新的各种python机器学习资源汇集列表
- [**Jupyter及相关工具资源大全**](https://github.com/HanXinzi-AI/awesome-jupyter-resources): 周更新的各种Jupyter及相关工具资源汇集列表
- [**NLP项目和资源大全**](https://github.com/HanXinzi-AI/awesome-NLP-resources): 周更新的各种NLP板块涉及的项目和工具资源汇集列表
