# Cosmetics Image Classifier
Data science project using deep learning for image classification

## Summary
For this project I built a ball classifier to identify balls from different sports. This could be useful for someone 
who is new to Cosmetic Field. They could take a picture of a cosmetic product and an app could serve them some information about 
the history and rules of the game. This is the underlying model for building something with those capabilities.

I was able to get the model to predict the cosmetic product with about 70%
accuracy after minimal tuning. For most of the cases this would 
meet the need of an end user of the app. To get these results I used transfer learning on a CNN trained on resnet34. 
This created time efficiencies and solid results.

<img src="https://github.com/yoonhaK/cosmetics_image_recognition/blob/master/confusion_matrix.png" width="500"/>

## Notes
It is based of the [fastai lesson two notebook](https://github.com/fastai/course-v3/blob/master/nbs/dl1/lesson2-download.ipynb)


## Data
I used the following chrome extension to download the data from google images. [FatKun Batch Download Image](https://chrome.google.com/webstore/detail/fatkun-batch-download-ima/nnjjahlikiabnchcpehcpkdeckfgnohf?hl=en)
