# Blindness Detection Image Recognition

----
## Background

**Problem Statement**: 

- Diabetic retinopathy  is the most common cause of vision impairment and blindness. It is caused by damage to the blood vessels of the light-sensitive tissue at the back of the eye (retina). 
- From 2010 to 2050, the number of diabetic retinopathy is expected to nearly double, from 7.7m to 14.6m in the US.



----
### Objective:

The purpose of this project is to create model that couldcorrectly classify the five stages of the disease, given the images of different patients.
- 0 - No DR
- 1 - Mild
- 2 - Moderate
- 3 - Severe
- 4 - Proliferative DR

----
### Data:

- The dataset contains 3662 images for both train and test data
- Each image is around 2k * 1.5k 
- Download: https://www.kaggle.com/c/aptos2019-blindness-detection/data

----
### Exploratory Data Analysis:

<p align="center">
  <img src="https://github.com/yuling0330/Blindness_Detection_Image_Recognition/blob/master/presentation/pca.PNG" />
</p>

----
### Models:

- PCA with Random Forest
- ResNet-50
- EfficientNetB5

----
### Results:
- Best modeling results using EfficientNetB5
<p align="center">
  <img src="https://github.com/yuling0330/Blindness_Detection_Image_Recognition/blob/master/presentation/final_resutls.PNG" />
  <img src="https://github.com/yuling0330/Blindness_Detection_Image_Recognition/blob/master/presentation/final_results2.PNG" />
</p>
