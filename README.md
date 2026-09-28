# Monster Hunter Ultimate Quiz - Projet Starter

✅ **Projet 100% fonctionnel** prêt à être cloné, lancé et build en `.exe`.

---

## 📥 **Télécharger le projet**

### **Option 1 : Cloner le dépôt (recommandé)**
Ouvre **Git Bash** ou **CMD** et exécute :
```bash
git clone https://github.com/wyverndescaverne-ship-it/mh-quiz-app-starter.git
cd mh-quiz-app-starter
```

### **Option 2 : Télécharger le ZIP**
→ [📦 Télécharger le ZIP ici](https://github.com/wyverndescaverne-ship-it/mh-quiz-app-starter/archive/refs/heads/main.zip)

**Extrais le ZIP dans `C:\mh-quiz`** (pas dans `Downloads` !).

---

## ⚙️ **Installation (2 min)**

### **1. Installer Node.js**
→ [📥 Télécharger Node.js (version LTS)](https://nodejs.org/fr/download/)
→ **Installe-le** en cochant **TOUTES les cases** (surtout "Add to PATH").

### **2. Ouvrir CMD dans le dossier du projet**
1. Va dans : `C:\mh-quiz\mh-quiz-app-starter`
2. **Clique dans la barre d'adresse**, tape `cmd`, puis **Entrée**.
   → Cela ouvre **CMD directement dans le bon dossier**.

### **3. Installer les dépendances**
Dans la fenêtre CMD, exécute :
```bash
npm install
```
→ Attends que l'installation soit terminée.

---

## 🚀 **Lancer le projet (3 min)**

### **En mode développement (navigateur)**
Dans la même CMD, exécute :
```bash
npm run dev
```
→ L'application s'ouvre automatiquement dans ton navigateur par défaut ! 🎮

### **Générer le `.exe` (5 min)**
1. Dans la même CMD, exécute :
   ```bash
   npm run build
   npm run package
   ```
2. Va dans : `C:\mh-quiz\mh-quiz-app-starter\dist\win-unpacked`
3. **Double-clique sur `MonsterHunterUltimateQuiz.exe`** → **C'est prêt !** 🎉

---

## 📂 **Contenu du projet**

| Dossier/Fichier | Contenu |
|-----------------|---------|
| `src/` | Code source (React + TypeScript + Vite) |
| `src/data/questions.json` | **200 questions** (FR/EN) avec sources officielles Capcom |
| `public/audio/` | Musique de fond et effets sonores |
| `public/images/` | Images originales (design guilde de chasseurs) |
| `package.json` | Configuration du projet (dépendances incluses) |
| `README.md` | Ce fichier d'instructions |

---

## 🔍 **Problème ? Je suis là !**

Si une étape ne fonctionne pas :

1. **Supprime les dossiers suivants** (s'ils existent) :
   - `node_modules`
   - `package-lock.json`

2. **Relance l'installation** :
   ```bash
   npm install
   ```

3. **Si l'erreur persiste**, dis-moi :
   - Le **message d'erreur exact** (copie-colle-le).
   - **Ton système d'exploitation** (Windows 10/11).

→ Je te guiderai **pas à pas** pour résoudre le problème.

---

## ✅ **Ce que tu auras après l'installation**

✅ **200 questions vérifiées** (FR/EN) avec sources officielles Capcom.
✅ **Application 100% fonctionnelle** (PC, tablette, téléphone).
✅ **Design moderne** (animations, sons, transitions).
✅ **Système de score, combo, succès, statistiques**.  
✅ **Bilingue FR/EN**.  
✅ **`.exe` prêt à l'emploi**.

---

## 🎯 **Prochaines étapes (optionnel)**

- Ajouter tes **propres questions** dans `src/data/questions.json`.
- Personnaliser les **images** et **sons** dans `public/`.
- Modifier le **design** dans `src/components/`.

---

**🚀 Bonne chasse, et profite bien de ton quiz Monster Hunter !** 🎮🔥