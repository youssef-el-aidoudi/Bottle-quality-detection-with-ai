# Détection de conformité des bouteilles

## Description

Ce projet utilise un modèle de Deep Learning pour détecter si une bouteille est **conforme** ou **non conforme** à partir d'une image.

Le modèle est implémenté en **Python avec TensorFlow/Keras** et utilise un **réseau de neurones convolutif (CNN)** pour la classification d’images.


---

## Dataset

Le dataset utilisé pour entraîner le modèle peut être téléchargé ici :

https://www.kaggle.com/datasets/localbrain/bottles

Le dataset peut aussi être enrichi en ajoutant des images prises avec une caméra ou un smartphone

Les images doivent être organisées avec la structure suivante :

dataset_qc/

train/
conforme/
non_conforme/

val/
conforme/
non_conforme/

test/
conforme/
non_conforme/


Le dataset peut aussi être enrichi en ajoutant des images prises avec une caméra.

---

## Fichiers du projet

- `train.py` : entraînement du modèle
- `model.py` : définition du modèle
- `data_loader.py` : chargement des images
- `evaluate.py` : évaluation du modèle
- `config.py` : paramètres du projet
- `utils.py` : fonctions utilitaires

---

## Installation

Installer les dépendances :  pip install -r requirements.txt


---

## Entraînement

Pour entraîner le modèle :
python train.py

---

## Technologies utilisées

- Python
- TensorFlow
- Deep Learning

