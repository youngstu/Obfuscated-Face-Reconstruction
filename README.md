# BME 595 Final Project
## Obfuscated Face Reconstruction
Estimating a high-resolution(HR) face image from its low-resolution(LR) counterpart using deep convolutional neural network. And using pretrained image classification model like VGGNet to contruct perceptual loss to obtain photo-realistic reconstruction. Plus, we may implement GAN(generative adversial network) and prior model to reconstruct the fine details.  
## Team members
Tong Shen (shen338), Jieqiong Zhao (JieqiongZhao)
## Goals
* Reconstruct obfuscated face using deep convolutional neural network following these steps: 
1. Construct efficient CNN structures to directly map LR face image to HR face image
2. Use pretrained model to develop perceptual loss combined with pixel-wise loss to evaluate the difference between the LR face image and the target HR face image
3. Use generative adversial network to reconstruct the fine details in the HR image
## Challenges
* Large datasets collection
  Compare the results of benchmark datasets applied in state of art super-resolution image reconstruction projects and find out the proper dataset to apply in our project
* High frequency information restoration 
  Reconstruct the high resolution images using limited information provided in low resolution image. The methods applied to estimate the high frequency infomation is critical and crucial.  
* Improve the speed of the computation 
  The prominent existing algorithms costs large amount of compuation resource (GPUs) and time. It would be difficult to develop an algorithm that both efficient and accurate.  
## Restrictions

## Example of LR Masaiced Image(left) vs. HR Image(center) vs. LR Blurred Image(right)

 ![](https://raw.githubusercontent.com/shen338/DL/master/lowresimage-example.jpg)
