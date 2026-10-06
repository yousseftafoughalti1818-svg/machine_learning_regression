# Machine Learning – Régression

Mise en pratique de la **régression linéaire** avec Python et Scikit-learn : régression simple et multiple, traitement des variables catégorielles, et implémentation de la **descente de gradient à la main** pour comprendre ce que fait l'algorithme.

## Projets

| Projet | Méthode | Problème | Résultat |
|---|---|---|---|
| [car-price-multiple-linear-regression](car-price-multiple-linear-regression) | Régression linéaire multiple | Prix de revente d'une voiture selon le kilométrage et l'âge | **R² = 0,88** sur les données de test |
| [categorical-house-price-regression](categorical-house-price-regression) | Régression linéaire + encodage One-Hot | Prix d'une maison selon la surface et la ville | **R² = 0,96** (entraînement) |
| [house-price-linear-regression](house-price-linear-regression) | Régression linéaire simple | Prix d'une maison selon la surface, avec sauvegarde du modèle (Joblib) | Équation prix = a × surface + b |
| [linear-regression-gradient-descent](linear-regression-gradient-descent) | Descente de gradient codée avec NumPy | Comparaison avec `LinearRegression` de Scikit-learn ; prédiction de salaires (3 variables) | Mêmes coefficients que Scikit-learn |

## Ce que j'ai appris

- **Préparer les données** : traitement des valeurs manquantes, conversion de texte en nombres, séparation entraînement / test.
- **Encoder des variables catégorielles** : variables indicatrices avec Pandas (`get_dummies`) et `OneHotEncoder` de Scikit-learn, en supprimant une colonne pour éviter la colinéarité (piège des variables indicatrices).
- **Comprendre l'optimisation** : la descente de gradient minimise l'erreur quadratique moyenne (MSE) en mettant à jour la pente et l'ordonnée à l'origine pas à pas, avec un critère d'arrêt.
- **Évaluer et interpréter** : coefficient de détermination R², lecture des coefficients du modèle, comparaison entre valeurs réelles et prédites.
- **Réutiliser un modèle** : sauvegarde et rechargement avec Joblib.

## Technologies

Python · Pandas · NumPy · Scikit-learn · Matplotlib · Joblib · Jupyter Notebook

## Lancer les notebooks

```bash
pip install numpy pandas matplotlib scikit-learn joblib
jupyter notebook
```

---

**Youssef Tafoughalti** · Étudiant en Master Ingénierie des Systèmes Complexes (EILCO) · En recherche de stage de fin d'études en Data Science / Machine Learning à partir de février 2027
📧 yousseftafoughalti1818@gmail.com
