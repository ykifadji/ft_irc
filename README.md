# ft_irc - Serveur IRC en C++98 🚀

## 📖 Description du projet

**ft_irc** est un projet visant à créer un serveur IRC, un protocole de communication textuel, en utilisant uniquement du C++98. Les utilisateurs peuvent se connecter au serveur avec un client IRC pour échanger des messages sur des canaux ou en privé.

👨‍💻 Ce projet a été réalisé en équipe avec deux autres personnes. J'ai principalement travaillé sur la gestion des canaux, en implémentant des fonctionnalités telles que l'authentification, la gestion des utilisateurs, et les commandes spécifiques aux opérateurs.

---

## 🎯 Fonctionnalités principales

- ⚡ **Support de plusieurs clients simultanés** grâce à des sockets non bloquants.
- 💬 **Commandes IRC implémentées** :
  - **KICK** : Éjecter un utilisateur d'un canal.
  - **INVITE** : Inviter un utilisateur à rejoindre un canal.
  - **TOPIC** : Modifier ou afficher le sujet d'un canal.
  - **MODE** : Configurer les paramètres d'un canal (mot de passe, limite d'utilisateurs, etc.).
- 🔐 **Authentification** : Connexion sécurisée via un mot de passe.
- 🔄 **Diffusion des messages** : Tous les utilisateurs d'un canal reçoivent les messages envoyés.

---

## 📚 Ce que j'ai appris

Ce projet m'a permis d'approfondir mes connaissances dans plusieurs domaines :

- 🌐 **Programmation réseau** : Maîtrise de l'utilisation des sockets TCP/IP et des E/S non bloquantes.
- 🛠️ **C++98** : Respect strict des standards du langage pour garantir une compatibilité totale.
- 📡 **Protocole IRC** : Compréhension et mise en œuvre des commandes clés.
- 🤝 **Travail en équipe** : Collaboration étroite avec mes coéquipiers pour intégrer nos travaux et résoudre ensemble les défis rencontrés.

---

## 🛠️ Technologies et outils utilisés

- **Langage** : C++98 ✨
- **Fonctions système autorisées** : 
  - `socket`, `recv`, `send`, `poll`, et d'autres pour la gestion des communications réseau.
- **Client de test** : Utilisation d'un client IRC standard pour valider le serveur.

---

## 🚀 Configuration et exécution

Pour compiler et exécuter le serveur, suivez ces étapes :

1. 📂 Clonez le dépôt Git.
2. ⚙️ Compilez le projet avec le Makefile :
   ```bash
   make
3. Démarrez le serveur :
   ```bash
   ./ircserv <port> <password>
## 🤝 Contributions

- **Ma partie** : Gestion des canaux, notamment :
  <br>
  • 🔐 Authentification des utilisateurs.
  <br>
  • 🛡️ Commandes (KICK, INVITE, TOPIC, MODE).
  <br>
  • 🔄 Diffusion des messages au sein des canaux.
- **Travail en équipe** : Coordination avec mes coéquipiers pour l’intégration des fonctionnalités et le débogage.
