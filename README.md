# 🎯 Classification des données des télescopes gamma avec l'IA

Ce projet vise à construire un système intelligent capable de classifier les données issues des télescopes gamma en utilisant des techniques d'apprentissage automatique et profond, et à le déployer via une application web utilisant Flask.

---

## 🧭 Table des matières

1. [Résumé](#-résumé)  
2. [Introduction générale](#-introduction-générale)  
3. [État de l’art](#-1-État-de-lart)  
4. [Conception du système intelligent](#-2-conception-du-système-intelligent)  
5. [Résultats](#-3-résultats)  
6. [Conclusion générale](#-conclusion-générale)  
7. [Annexes](#-annexes)  
8. [Installation](#-installation)  
9. [Utilisation](#-utilisation)  
10. [Technologies utilisées](#-technologies-utilisées)  
11. [Auteur](#-auteur)  
12. [Licence](#-licence)

---

## 📄 Résumé

Ce projet explore les caractéristiques des rayons gamma détectés par des télescopes, analyse les jeux de données correspondants et applique différentes approches de machine learning et de deep learning pour construire un modèle de classification robuste.

---

## 🚀 Introduction générale

L’objectif est de développer un système intelligent permettant de classifier automatiquement les événements détectés par les télescopes gamma, à partir de données complexes et multidimensionnelles.

---

## 📚 1. État de l’art

- **Observatoires gamma**  
- **Types de rayonnements ionisants** : alpha, bêta, gamma  
- **Apprentissage automatique et profond**  
- **Types d'apprentissage** : supervisé, non supervisé, par renforcement

---

## 🛠️ 2. Conception du système intelligent

- Approche globale et pipeline complet  
- Analyse exploratoire des données : statistiques, corrélations, outliers, répartition  
- Prétraitement : encodage, normalisation, équilibrage  
- Implémentation de modèles : SVM, RandomForest, XGBoost, etc.  
- Implémentation d’un réseau de neurones (ANN)  
- Déploiement avec **Flask**

---

## 📊 3. Résultats

- Comparaison des modèles de machine learning avec GridSearchCV et RandomizedSearchCV  
- Évaluation des performances (accuracy, f1-score, etc.)  
- Résultats obtenus avec les réseaux de neurones  
- Présentation de l’interface Flask du modèle déployé

---

## 🧾 Conclusion générale

La conclusion récapitule les performances obtenues, les leçons tirées de l’expérimentation, et les perspectives futures pour l’amélioration du système intelligent.

---

## 📎 Annexes

- ANNEXE A :la théorie des modèles utilisées  
- ANNEXE B : la déstribution des variables pour vérifier est ce que normalisé ou pas

---

## 🧩 Installation

1. Cloner le projet :
```bash
git clone https://github.com/yelwali/classification-gamma-telescope.git
cd classification-gamma-telescope

## 🧩 Installer les dépendances :
pip install -r requirements.txt
## 🧩 Lancer le projet
python app.py
