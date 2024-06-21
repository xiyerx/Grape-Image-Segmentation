This repository contains the implementation of various deep learning architectures for the segmentation of grape images. These include variants of U-Net, SegNet and Fully Convolutional Networks (FCNs). The performance of these models is assessed using metrics like accuracy, Dice coefficient, Intersection over Union (IoU), and focal loss.

## Segmentation Models
The following segmentation models are implemented:
- [Basic Autoencoder](Shwetha_Basic%20Autoencoder.ipynb)
- [FCN32](Shwetha_FCN32.ipynb)
- [FCN8](Shwetha_FCN8.ipynb)
- [SegNet-1](Shwetha_SEGNET1.ipynb)
- [SegNet-2](Shwetha_SEGNET2.ipynb)
- [VGG16-SegNet](Shwetha_VGG16SegNet.ipynb)
- [UNet-1](Shwetha_UNET1.ipynb)
- [UNet-2](Shwetha_UNET2.ipynb)
- [ResNet34-UNet](Shwetha_ResNet34+UNET.ipynb)
- [MobileNetV2-UNet](Shwetha_MobileNetV2+UNET.ipynb)


## Dataset
The dataset used for training the models is GrapesNet, which includes over 11,000 images of grape bunches captured under various conditions. A subset of these images was manually annotated to create binary masks for training. Data augmentation techniques such as zooming, flipping, and contrast changes were applied to increase the dataset size and improve model generalization.

## Results
*attach images here*
