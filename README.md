# 🧠 Neural Network — Moons Classification

This project builds a simple **neural network classifier** on the well-known **two-moons dataset**, introducing the essentials of deep learning: data generation, preprocessing, neural network architecture design, training, evaluation, and visualization.  
It is a great foundational project for understanding how neural networks learn non-linear patterns.

---

## 🌙 Project Overview

This project demonstrates:

- Generating and visualizing the **moons dataset**
- Building a neural network with Keras/TensorFlow
- Training and evaluating the model
- Visualizing the learning curve
- Making predictions on unseen data

---

## 🗂️ Repository Structure

.
├── your_first_neural_network.ipynb # Main notebook with full workflow
├── moons_example.png # Optional dataset visualization
├── utils/ # Helper functions
├── tests/ # Unit tests (if provided)
├── Makefile
└── README.md


---

## 📊 Dataset — Two Moons

We use the synthetic dataset `make_moons` from scikit-learn.  
It contains two interleaving half-circles, making it ideal for non-linear classification.

```python
from sklearn.datasets import make_moons

X, y = make_moons(n_samples=500, noise=0.2, random_state=0)

🧱 Neural Network Architecture

The model is simple but effective for binary classification:

Input layer: 2 features

Hidden layer: 5 neurons, ReLU

Output layer: 1 neuron, Sigmoid
