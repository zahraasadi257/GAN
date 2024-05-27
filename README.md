# GAN
This repository contains a *PyTorch* and **PyTorch Lightning** implementation of a Generative Adversarial Network (GAN) designed to generate digit images similar to those found in the **MNIST dataset**. The `MNISTDataModule` class handles data loading and preprocessing, ensuring that the data is ready for model training. The GAN consists of two main components: the **`Generator`** and the **`Discriminator`**. The **`Generator`** takes a latent space vector and upsamples it to produce a digit image, while the **`Discriminator`** evaluates whether an image is real (from MNIST) or fake (produced by the `Generator`). Training involves alternating between optimizing these two networks against each other, with the `Discriminator` trying to get better at distinguishing real from fake, and the `Generator` trying to produce increasingly convincing images. The code includes detailed forward methods for both models and a training loop that manually optimizes both networks using the **Adam optimizer**. 



![GAN](https://github.com/zahraasadi257/GAN/assets/57061013/1ce124c8-6c4b-4996-934f-79e574c07646)
