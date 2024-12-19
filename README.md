# DA-SDNS 【一种深度自适应地震数据噪声压制算法】
This is a random noise suppression algorithm for seismic signals based on depth adaptive fuzzy computing

本算法主要包含两部分，分别是python神经网络部分和matlab绘图部分。其中，python版本采用python3.11，matlab版本采用R2024a。python深度学习神经网络采用了（Convolutional Architecture for Fast Feature Embedding，Caffe）架构编写。如果您想学习修改本代码，建议参看https://caffe.berkeleyvision.org/。（温馨提示：请下载后自行修改，不要上传在本GitHub中！！！）

Cython>=0.19.2
numpy>=1.7.1
scipy>=0.13.2
scikit-image>=0.9.3
matplotlib>=1.3.1
ipython>=3.0.0
h5py>=2.2.0
leveldb>=0.191
networkx>=1.8.1
nose>=1.3.0
pandas>=0.12.0
python-dateutil>=1.4,<2
protobuf>=2.5.0
python-gflags>=2.0
pyyaml>=3.10
Pillow>=2.3.0
six>=1.1.0
