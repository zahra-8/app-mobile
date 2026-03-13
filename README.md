# LimArgent 

**LimArgent** est une application Android moderne de gestion de finances personnelles développée en Kotlin. Elle permet aux utilisateurs de suivre leurs revenus et dépenses, de visualiser leur santé financière via des graphiques et de gérer des objectifs d'épargne précis.

##  Fonctionnalités principales

- **Gestion des Transactions** : Ajoutez, modifiez ou supprimez vos revenus et dépenses en quelques clics.
- **Tableau de Bord Dynamique** : Visualisez votre solde actuel, le total des revenus et des dépenses du mois en un coup d'œil.
- **Analyses Visuelles** : Un graphique circulaire (Pie Chart) personnalisé pour comprendre la répartition de vos dépenses par catégorie.
- **Objectifs d'Épargne** : Créez des projets (ex: Vacances, PC Gamer), suivez votre progression avec une barre visuelle et épargnez efficacement.
- **Récurrences Automatiques** : Gérez vos mouvements récurrents (loyer, abonnements) qui sont générés automatiquement chaque mois.
- **Alertes de Budget** : Définissez un seuil de sécurité et recevez une notification si votre solde devient trop bas.
- **Recherche & Filtres Avancés** : Retrouvez n'importe quelle transaction par titre, catégorie ou période.

## Stack Technique

- **Langage** : Kotlin
- **Interface** : Android XML avec Material Design 3
- **Base de données** : Firebase Cloud Firestore (Synchronisation en temps réel)
- **Authentification** : Firebase Auth (Email/Mot de passe)
- **Notifications** : Android Notification Manager (Alertes de seuil)
- **Architecture** : Pattern Manager avec écouteurs (listeners) pour une UI réactive.

##  Installation et Utilisation

1. **Cloner le projet** :
   ```bash
   git clone https://gitlab.com/votre-lien/limargent.git
