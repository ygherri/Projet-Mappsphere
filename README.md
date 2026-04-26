# MappSphere 🌍

MappSphere est une application web développée avec Angular et Firebase.  
Elle permet à l’utilisateur de se connecter avec Google, d’afficher sa position sur une carte interactive et de consulter la météo actuelle de sa localisation.

## 🚀 Démo en ligne

Lien de l'application :  
https://mappsphere.firebaseapp.com

## ✨ Fonctionnalités

- Connexion avec Google
- Authentification avec Firebase Authentication
- Affichage de la position actuelle de l’utilisateur
- Carte interactive avec Leaflet et OpenStreetMap
- Récupération de la météo selon la géolocalisation
- Affichage de la ville et de la température actuelle
- Enregistrement de l’historique météo
- Déconnexion de l’utilisateur
- Interface responsive

## 🛠️ Technologies utilisées

- Angular 17
- TypeScript
- Firebase
- Firebase Authentication
- Firestore
- AngularFire
- Leaflet
- OpenStreetMap
- OpenWeatherMap API
- RxJS
- Tailwind CSS
- HTML5
- CSS3

## 📦 Installation en local

Cloner le projet :

```bash
git clone https://github.com/ygherri/Projet-Mappsphere.git
```

Accéder au dossier :

```bash
cd Projet-Mappsphere
```

Installer les dépendances :

```bash
npm install
```

Lancer le serveur de développement :

```bash
ng serve
```

Ouvrir l'application :

```text
http://localhost:4200/
```

## 🔥 Configuration Firebase

Le projet utilise Firebase pour l’authentification Google et le stockage de l’historique météo.

Exemple de configuration Firebase :

```ts
export const environment = {
  production: false,
  firebaseConfig: {
    apiKey: "VOTRE_API_KEY",
    authDomain: "VOTRE_AUTH_DOMAIN",
    projectId: "VOTRE_PROJECT_ID",
    storageBucket: "VOTRE_STORAGE_BUCKET",
    messagingSenderId: "VOTRE_MESSAGING_SENDER_ID",
    appId: "VOTRE_APP_ID"
  }
};
```

## 🌦️ API météo

L’application utilise une API météo pour récupérer les données en fonction de la latitude et de la longitude de l’utilisateur.

Exemple de données affichées :

- ville actuelle ;
- température actuelle ;
- historique météo par date.

## 🗂️ Routes principales

| Route | Description |
|---|---|
| `/home` | Page d’accueil et connexion Google |
| `/dashboard` | Carte, position actuelle et météo |
| `/history` | Historique météo |
| `**` | Page 404 |

## 🏗️ Build

Créer une version de production :

```bash
ng build
```

Les fichiers générés se trouvent dans le dossier :

```text
dist/
```

## 👩‍💻 Auteur

Projet développé par **GHERRI Yesmine**.

GitHub :  
https://github.com/ygherri