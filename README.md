# Multimodal-Brain-Tumour-Segmentation

Brain Tumor Segmentation using a 3D UNet CNN


This U-Net was built for the [MICCAI BraTS dataset][BraTS]. This U-Net was based on the one constructed in [this paper (Isensee 2017)][Isensee 2017]. The [original U-Net paper](https://arxiv.org/abs/1505.04597) is from 2015, so the architecture is still quite new. It performs extremely well for segmentation tasks that require a lot of precision and for which there is not a lot of example data. There were a total of 285 patients in this dataset. Typically, for neural networks to be trained well on image classification tasks, there are tens of thousands of example training images.

## BRATS Dataset 
I have used BRATS 2017 training dataset for the analysis of the proposed methodology. It consists of real patient images as well as synthetic images created by MICCAI. Each of these folders are then subdivided into High Grade and Low Grade images. For each patient, four modalities(T1, T1-C, T2 and FLAIR) are provided. The fifth image has ground truth labels for each pixel. The dimensions of images are (240,240,155) in both.

### 3D U-Net Architecture :

![](Images/3dunet.png)
