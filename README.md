# ofxDarknet

ofxDarknet is a openFrameworks wrapper for darknet.

Darknet is an open source neural network framework written in C and CUDA. It is fast, easy to install, and supports CPU and GPU computation. http://pjreddie.com/darknet/

## Features

### YOLO: Real-Time Object Detection aka Dense Captioning (http://pjreddie.com/darknet/yolo/)

Running this on a notebook with a NVidia K1000M graphics card takes about 350ms, so ~3fps.

![YOLO2](https://raw.githubusercontent.com/mrzl/ofxDarknet/master/images/yolo2.jpg)

### Imagenet Classification (http://pjreddie.com/darknet/imagenet/)

On the same hardware, this runs at ~30fps.

![Classification](https://raw.githubusercontent.com/mrzl/ofxDarknet/master/images/imagenet_classification.jpg)

### Deep Dream (http://pjreddie.com/darknet/nightmare/)

640x480 image uses 1.5gb ram on your graphics card. Depending on the parameters this can take from seconds up to minutes.

![DeepDream](https://raw.githubusercontent.com/mrzl/ofxDarknet/master/images/deep_dream.jpg)

### Recurrent Neural Network (http://pjreddie.com/darknet/rnns-in-darknet/)

![RNN](https://raw.githubusercontent.com/mrzl/ofxDarknet/master/images/rnn.jpg)

## Setup

### Windows

Install the dependencies for building darknet on Windows 10:
* [Visual Studio 2015 (Community)](https://www.microsoft.com/download/details.aspx?id=48146)
* [CUDA 8.0 64bit](https://developer.nvidia.com/cuda-downloads)
* [OpenCV 2.4.9](https://sourceforge.net/projects/opencvlibrary/files/opencv-win/2.4.9/opencv-2.4.9.exe/download)

### OSX

An OSX version is on the way and will be updated here..