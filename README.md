# Autour — PWA Cameroun

Cette version s’installe depuis un navigateur mobile compatible et garde la page d’accueil disponible hors ligne après sa première visite.

## Publication

Publiez **tout le contenu de ce dossier** sur un hébergement web statique qui sert le site en HTTPS. Le fichier `index.html` doit être à la racine de l’adresse publiée, avec `manifest.webmanifest`, `service-worker.js` et `icon.svg` au même niveau.

Une fois le site en ligne :
- Android : ouvrez l’adresse dans Chrome et choisissez **Installer l’application** ou **Ajouter à l’écran d’accueil**.
- iPhone : ouvrez l’adresse dans Safari, touchez **Partager**, puis **Sur l’écran d’accueil**.

Le bouton d’installation intégré apparaît dans les navigateurs Android qui exposent l’invite d’installation. La PWA n’est pas un fichier APK; elle nécessite une adresse HTTPS publique pour être installée par le public.
