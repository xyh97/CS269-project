# CS269 FinalProject

Study the Robustness of Self-Attentive Models

Slides can be found in [Google Drive](https://drive.google.com/open?id=1ZlvUNdGyTjealmBcmtGkSyXXXvtGd7W1).

# Descriptions
1. Download Zhang's dataset for [Yelp](https://drive.google.com/drive/u/0/folders/0Bz8a_Dbh9Qhbfll6bVpmNUtUcFdjYmF2SEpmZUZUcVNiMUw1TWN6RDV3a0JHT3kxLVhVR2M), and [MNLI](https://www.nyu.edu/projects/bowman/multinli/).
2. Run fine-tuning on Yelp and MNLI using BERT code, *bert.py* adapted from https://github.com/huggingface/transformers.
3. Implement simple LSTM models and also train them on the above datasets like shown in *bilstm_att.py*.
4. Attention scores of BERT can be obtained using [Transformers](https://github.com/huggingface/transformers).
5. I attached a jupyter notebook *attack.ipynb* that was used during our experiments. Steps for conducting attack are demonstrated therein.
6. *plot.ipynb* is what we use for figure plotting.