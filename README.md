## DistilBERT Sentiment Classifier with Hugging Face Transformers (IMDb Dataset)

This project demonstrates how to fine-tune a pre-trained `DistilBERT` model using the [IMDb dataset](https://huggingface.co/datasets/imdb) for binary sentiment classification (positive vs. negative movie reviews). The model is built using the `Hugging Face Transformers` library and evaluated using common NLP metrics.

---

## 🚀 Features

- Utilizes Hugging Face `transformers` and `datasets` libraries
- Fine-tunes `distilbert-base-uncased` for binary classification
- Includes preprocessing, model training, evaluation, and custom predictions
- Evaluates using accuracy, precision, recall, and F1-score
- Contains a simple sentiment prediction function for new text

---

## 🧠 Model Overview

- **Architecture**: DistilBERT (base uncased)
- **Dataset**: IMDb movie reviews (subset for demo)
- **Training**: 3 epochs, batch size 8, learning rate 2e-5
- **Metrics**: Accuracy, Precision, Recall, F1-score

---

## 📦 Requirements

Install dependencies with:

```bash
pip install transformers datasets
