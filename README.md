
# LAB-17-Cracker-OWASP-Uncrackable-Android-Level-3
## Prérequis
![](https://github.com/user-attachments/assets/7e97d061-506e-4ee7-8f6b-10ab6a172f75)
![](https://github.com/user-attachments/assets/096f38cf-a0b1-450a-8842-6b55b6fc50e7)
## Étape 1 : Analyse statique simple avec Jadx-GUI (comprendre le Java)
![](https://github.com/user-attachments/assets/bfbba835-70b1-4a63-be57-330dc436033f)
![](https://github.com/user-attachments/assets/c558b60d-9abe-488a-ac93-49d75654a71f)
## Étape 2 : Décompiler l’APK avec apktool
![](https://github.com/user-attachments/assets/cc922b42-cccc-4be1-86ce-a706cb97d864)
![](https://github.com/user-attachments/assets/5305cc75-5314-4bca-a26b-0199bcdf8c9f)
## Étape 3 : Patch smali – Supprimer le message « tampered » / root
### 1. Ouvrir le bon fichier
![](https://github.com/user-attachments/assets/774a0254-fcfd-40ed-a244-437263d999f9)
### 2. Chercher le bloc d’erreur (Ctrl + F)
![](https://github.com/user-attachments/assets/a7e63469-2e08-43fc-a251-c3475f1fe22a)
### 3. Le bloc exact à modifier 
![](https://github.com/user-attachments/assets/9cb7c8d6-3d85-4cbc-9eeb-83869de9bcd0)
### 4. Deux méthodes de patch
![](https://github.com/user-attachments/assets/4e5ab799-95c2-49ae-894f-8f4d59afddc8)
![](https://github.com/user-attachments/assets/376df0e8-bf48-4022-b5f6-9167be719710)
### 5. Sauvegarder
En appuiant sur Ctrl + S 
### 6. Recompiler l’APK
![](https://github.com/user-attachments/assets/163708d2-0107-409e-9a0b-dd57ba1fa9f6)
### 7. Signer l’APK
![](https://github.com/user-attachments/assets/44020980-3827-4737-87a4-07f3b400c6f2)
### 8. Installer et tester
![](https://github.com/user-attachments/assets/28439ee8-4880-4abc-acbc-e71dd0709c64)
![](https://github.com/user-attachments/assets/f8b7c33e-c92a-47a5-9cec-e9a02c22c4a7)
## Étape 4 : Patch de la librairie native avec Ghidra
![](https://github.com/user-attachments/assets/2e10ff37-22ef-4719-8cb2-9ed37e7d4650)
![](https://github.com/user-attachments/assets/5daa1aab-037e-4740-b555-556626bd1010)
## Étape 5 : Analyser la logique native de vérification dans libuncrackable3.so
### 1. Revenir au point d’entrée Java
![](https://github.com/user-attachments/assets/9b11b53d-1642-4937-8689-49ba770d2304)
### 2. Retrouver la fonction native correspondante
![](https://github.com/user-attachments/assets/8be491ae-9b25-4f0c-b6f1-a9093c1a5f5b)
### 3. Observer la structure générale du pseudo-code
![](https://github.com/user-attachments/assets/ec5c5dca-9773-45d3-954e-3a197bf6e148)

## Vérification
![](https://github.com/user-attachments/assets/52394ee1-bf7d-4902-be3d-dfe62897bb16)
![](https://github.com/user-attachments/assets/25436806-3326-492e-838a-6fbafcd4af38)



![](https://github.com/user-attachments/assets/2429b7f7-0316-40fb-8fcd-8ea0ff0b2f48)
### 8. Installer et tester
![](https://github.com/user-attachments/assets/cec5856f-10fb-40b8-8422-848ac92b462f)
