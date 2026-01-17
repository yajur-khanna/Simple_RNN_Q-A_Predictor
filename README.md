# RNN-Based Question & Answer / Next-Word Predictor

A Recurrent Neural Network (RNN)–based language model that learns sequential dependencies in text to predict the **next word** given a context. This project demonstrates core NLP concepts including tokenization, embeddings, sequence modeling, and probabilistic text generation.

---

## Overview

This project implements a **from-scratch RNN pipeline** for next-word prediction:

- Text preprocessing and vocabulary construction  
- Word-to-index encoding  
- Embedding + RNN architecture  
- Training using cross-entropy loss  
- Inference via probabilistic sampling  

The model captures temporal dependencies in text, making it suitable as a foundation for **Q&A systems, text completion, and language modeling tasks**.

---

## Model Architecture

- **Embedding Layer** – Converts token indices into dense vectors  
- **Recurrent Neural Network (RNN)** – Learns sequential patterns  
- **Fully Connected Layer** – Maps hidden states to vocabulary logits  
- **Softmax** – Produces probability distribution over next-word candidates  

