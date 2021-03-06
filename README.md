# msds19077_COVID19_DLSpring2020
This repository contains code and results for COVID-19 classification assignment by Deep Learning Spring 2020 course offered at Information Technology University, Lahore, Pakistan. This assignment is only for learning purposes and is not intended to be used for clinical purposes.

# PART 1: Dataset
Dataset used for this assignment can be found using link blow: <a href="https://drive.google.com/file/d/1-HQQciKYfwAO3oH7ci6zhg45DduvkpnK/view?usp=sharing"></a>

# Task 1: Load pretrained CNN model and fine-tune FC Layers
Our task is to fine-tune Fully Connected layers of ResNet-18 and VGG-16 pretrained models by adding two custom layes and freezed other layer then train model on given dataset. And the results are given blow:
</br></br>
```ResNet-18 Results after find-tune FC Layers:```
</br></br>
![](Results/resnet18_FC_Control_curves.png)
![](Results/resnet18_FC_Control_results.png)

</br></br>
```VGG-16 Results after find-tune Classifier:```
</br></br>
![](Results/vgg16_FC_Only_curves.png)
![](Results/vgg16_FC_Only_results.png)

# Task 2: Fine-tune the CNN and FC layers of the network
Our task is to fine-tune Fully Connected and classifier layers of ResNet-18 and VGG-16 pretrained models by unfreezing different layes then train model on given dataset. And the results are given blow:

</br></br>
```ResNet-18 Results after unfreezing all layers:```
</br></br>
![](Results/resnet18_entire_curves.png)
![](Results/resnet18_entire_results.png)

</br></br>
```VGG-16 Results after unfreezing all layers:```
</br></br>
![](Results/vgg16_entire_curves.png)
![](Results/vgg16_entire_results.png)

# Trained Models:
<p>Trained weights for this dataset can be found using this link:</p><a href="https://drive.google.com/open?id=1evAZB1c9GfsWA-uiVcbebyGkt-2oFxBa">Link</a>


<hr>

# PART 2: Dataset
Dataset used for this assignment can be found using this link:  <a href="https://drive.google.com/file/d/1eytbwaLQBv12psV8I-aMkIli9N3bf8nO/view?usp=sharing">Link </a>
# Task:
In this task we are performing multi-class, multi-label classification by implementing focal loss for detecting infections such as COVID-19 among X-Ray images.

# Experiment 1:
```ResNet-18 with Binary Cross Entropy loss with logistics:```
![](Results/resnet18-bce.png)
</br>
```Confusion Matrix for validation data```
</br>
![](Results/resnet18-bce-CM-valid.png)

# Experiment 2:
```VGG-16 with Binary Cross Entropy loss with logistics:```

![](Results/vgg16-bce.png)
</br>
```Confusion Matrix for validation data```
</br>
![](Results/vgg16-bce-CM-valid.png)

# Experiment 3:
```ResNet-18 with Focal Loss:```

![](Results/resnet18-fl.png)
</br>
```Confusion Matrix for validation data```
</br>
![](Results/resnet18-fl-CM-valid.png)

# Experiment 4:
```VGG-16 with Focal Loss:```

![](Results/vgg16-fl.png)
</br>
```Confusion Matrix for validation data```
</br>
![](Results/vgg16-fl-CM-valid1.png)

# Comparison:
```If we compare all model results then we can clearly see that VGG-16 with binary cross entropy with logistic loss give us good results. The best model and accuracy parameters for this task is```
</br>
![](Results/model-compare.png)

# Trained Model:
Trained weights for this dataset can be found using this link:<a href="https://drive.google.com/open?id=1aTiVv7fDUqtbkrqM2e-LfjaTWkyfPu8d">Link</a>
