# MNIST Digit Recognizer Practice

Classification project using the MNIST digits dataset for introductory exploration of ANNs and CNNs. 

## Overview & Skills

- **Data preparation:** Reshaping MNIST digit data and visualizing raw pixel inputs to build intuition about the input space.
- **Baseline modeling:** Establishes a baseline model and explores performance of logistic regression on this problem.
- **Neural network experimentation:** Experiments with and compares deeper dense architectures using TensorFlow/Keras, plotting collected training vs validation data.
- **Exploring CNNs:** Implements and evaluates convolutional neural networks to capture spatial structure in the digit images, analysing how their training/validation behavior and generalization differ.
- **Regularization / early stopping:** Use early stopping to prevent overfitting and monitor generalization.
- **Evaluation & interpretation:** Computes and visualizes confusion matrices, analyzes misclassifications, and plots training/validation curves to understand model performance beyond raw accuracy.

## Running the notebook
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn tensorflow
