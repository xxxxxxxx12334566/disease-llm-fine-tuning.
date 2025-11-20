# disease-llm-fine-tuning.

# LLM Fine-Tuning for Disease Suggestion Based on Symptoms

This repository contains my project for fine-tuning a language model to suggest possible diseases based on input symptoms.

> ⚠️ This project is for educational purposes only. It must **not** be used for real medical diagnosis or treatment.

## Contents

- `Disease_Symptom_FineTuning.ipynb` – Google Colab notebook with:
  - Dataset loading
  - JSONL creation
  - Model fine-tuning (2 epochs)
  - Confusion matrix generation
  - Demo query tests
- `train.jsonl`, `test.jsonl` – processed training and test datasets
- `confusion_matrix.png` – confusion matrix for the model’s predictions
- `sample_output_demo_query.txt` – sample output of the demo query `Fever, headache, body pain`
- `disease_llm_adapter.zip` – zip of the LoRA adapter for the fine-tuned model

## Demo Query

Example query:

```text
Symptoms: Fever, headache, body pain
