# Cat vs. Dog Image Classification 

Utilize a Convolutional Neural Network (CNN) to classify images as either cats or dogs.

## Overview

The `CatVsDog Classification` provides a deep learning model to discern between images of cats and dogs. This is accomplished through the implementation of a CNN model using Keras.

## Dataset

The dataset used for this project is sourced from TensorFlow datasets and is available [here](https://www.tensorflow.org/datasets/catalog/cats_vs_dogs).

## Features

- **ImageDataGenerator**: For efficient image loading, augmentation, and real-time data feeding to the model.
  
- **CNN Architecture**:
  - 3 Convolutional layers each followed by a ReLU activation and MaxPooling.
  - A Flatten layer to transform 3D feature maps to 1D feature vectors.
  - Dense layers with ReLU and sigmoid activations.
  - Dropout for regularization.
  
- **Configurable Parameters**:
  - Image height and width: 150x150
  - Training samples: 2000
  - Validation samples: 800
  - Batch size: 16
  - Epochs: 50

## Prerequisites

1. Ensure Keras and TensorFlow are installed.
2. Download the dataset and arrange it in the appropriate directories (`training` and `validation`).

## Usage

1. Clone this repository:
    ```bash
    git clone [YOUR REPOSITORY LINK]
    cd [YOUR REPOSITORY FOLDER NAME]
    ```

2. Modify the paths (`train_data_dir` and `validation_data_dir`) in the script to point to your dataset directories.

3. Execute the script in your Python environment to start the training process.

## Model Summary

To get an overview of the model's architecture, call:
```python
classifier.summary()
