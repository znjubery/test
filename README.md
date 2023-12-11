# Test GitHub pages  
Example published repository  

# [SNAP : Soybean Nodule Acquisition Pipeline](https://github.com/znjubery/snap)  

This is a companion repository of the submitted manuscript "Using Machine Learning To Develop A Fully Automated Soybean Nodule Acquisition Pipeline (SNAP)". This repository is organized in three sections as presented in the manuscript.

Nodule detection: This section takes a root image as the input and draws bounding boxes around the detected nodules. The model was based on a RetinaNet on a ResNet50-FPN backbone. The model was trained using ~140 diverse root samples. The AP of the model on ~30 test samples was 0.62. The base code of this model was borrowed from https://github.com/fizyr/keras-retinanet. We introduced anchor selection based on the natural size distribution of nodules.



# [COFE : Core rOot Feature Extraction(https://bitbucket.org/baskargroup/cofe/src/master/)https://bitbucket.org/baskargroup/cofe/src/master/)  

Software developed to analyze crop plant's excavated mature root

### Features
COFE uses automated digital trimming of outlier roots to improve the estimation of root angles.
COFE is optimized for use on adult, field-grown plants.
Two steps process: image pre-processing and trait extraction. Image processing step faciliates user to annotate soil line.
COFE is an adaptation of our existing software ARIA (Pace et al. 2014) which was developed for lab-based phenotyping of immature root systems.
Modular framework that allows extensions.
GUI based framework for ease of use.


