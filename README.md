
<p align="center">
  <img src="https://github.com/xiaoxingxingkz/BrainTransGAN/blob/main/img/subject_s.gif" width="400">
</p>

# Multimodal Transformer Network for Incomplete Image Generation and Diagnosis of Alzheimer’s Disease

## Abstract

Deep learning has been widely investigated in brain image computing and analysis for disease diagnosis. Most of existing methods build the deep learning models to learn the features from brain images, followed by group analysis to classify diseases. It is still challenging to model the individual brain dynamics in disease for interpretable imaging and precision medicine. In this paper, we propose a generative model based on brain status transferring generative adversarial network (BrainStatTrans-GAN) to decode the individual differences of brain dynamics in Alzheimer’s Disease. The BrainStatTrans-GAN consists of 3 components which are generator, discriminator, and status discriminator. First, a generative adversarial network with generator and discriminator is built to generate the heathy brain images. Then, a status discriminator is added to the generator to produce the heathy brain images from the disease. Finally, the differences between the generated and real images are computed to decode the brain dynamics, which can be used for disease diagnosis and interpretation of brain changes. Compared to the existing group analysis, the proposed method can model the individualized brain dynamics in Alzheimer’s Disease which can facilitate the disease diagnosis and interpretation. Interpretable experiments on three datasets with 1739 subjects demonstrated that our BrainTransGAN can be used as a tool with superior properties for reconstructing healthy images and exploring whole brain dynamics. 

## Overview
<p align="center">
  <img src="https://github.com/xiaoxingxingkz/BrainTransGAN/blob/main/img/F1.png" width="700">
</p>

## Prerequisites

* Linux
* Python3.7
* MindSpore 2.0.0-alpha
* CPU or NVIDIA GPU + CUDA CuDNN


