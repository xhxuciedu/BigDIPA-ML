
# Big Data Image Processing & Analysis (BigDIPA): Intro to Machine Learning #

### Intro 
This repository contains Jupyter notebooks providing a brief introdcution of machine learning and applying it to medical/biological image analysis. 

It is the machine learning component of BigDIPA shortcourse offered at UC Irinve.  
http://bigdipa.ccbs.uci.edu/

### Getting Started

We recommend you install Python 2.7.X and associated modules (numpy, matplotlib, ect.) in one swoop with Anaconda. https://docs.continuum.io/

Once you have Anaconda installed, install the other three main requirements using pip.

Download/clone this repository to your local drive. You can then start the Jupyter notebook application and view the notebook in your local browser.  With all requirements installed, you can browse through the notebook executing one cell at a time.


### Requirements ###

* Python 2.7.X (recommend installing via Anaconda)
* Keras 2.0.7 (via pip)
* Tensorflow 1.3.0 (via pip)
* Openslide 3.4.1 (compile from source http://openslide.org/download/)
* Openslide Python interface 1.1.1 (via pip)


### Notes ###

The code was written with GPU access in mind. If GPU is not available, the training step will run quite slow.



### Application example: Pathology AI ###

As a specific application example, we will apply deep learning to perform breast cancer prediction on whole slide images of histological lymph node sections. At a high level, the method uses pretrained Inception V3 model learned on natural images and finetuned for the purpose of cancer prediction.
