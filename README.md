# Système Fluide – mettre l'appli en ligne (gratuit, ~5 min)

## 1. Mettre les fichiers sur GitHub
1. Crée un compte sur https://github.com (gratuit).
2. Clique **New repository**, nomme-le `systeme-fluide`, coche **Public**, puis **Create repository**.
3. Clique **uploading an existing file**, glisse **le contenu** du dossier (index.html, manifest.webmanifest, sw.js, le dossier icons), puis **Commit changes**.

## 2. Activer GitHub Pages
1. Dans le dépôt : **Settings → Pages**.
2. Source : **Deploy from a branch**, branche **main**, dossier **/ (root)**, puis **Save**.
3. Attends 1 à 2 minutes : ton appli est sur `https://TON-PSEUDO.github.io/systeme-fluide/`.

## 3. L'installer sur ton téléphone (Android, Chrome)
1. Ouvre l'adresse ci-dessus dans Chrome.
2. Menu **⋮ → Installer l'application** (ou **Ajouter à l'écran d'accueil**).
3. L'icône Système Fluide apparaît : elle s'ouvre en plein écran et marche hors ligne.

## À savoir
- Tes données sont enregistrées **sur le téléphone**, pas en ligne. Fais un **Réglages → Exporter** de temps en temps : si tu vides les données de Chrome, tu peux tout récupérer avec **Importer**.
- Pour passer sur un autre appareil : Exporter sur le premier, Importer sur le second.
- Le dépôt étant public, le code de l'appli est visible, mais **pas tes données** (elles restent sur ton téléphone).
- Pour une mise à jour de l'appli : remplace les fichiers sur GitHub et change `sf-v1` en `sf-v2` dans `sw.js`.
