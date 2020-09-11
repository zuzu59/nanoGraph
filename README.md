# nanoGraph
Récupération de données d'un API json et affichage graphique dans une page HTML statique sans serveur backend
zf200911.1635
<!-- TOC titleSize:2 tabSpaces:2 depthFrom:1 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 skip:1 title:1 charForUnorderedList:* -->
## Table of Contents
* [Buts](#buts)
* [Problématiques](#problématiques)
* [Moyens](#moyens)
* [Utilisation](#utilisation)
* [Sources](#sources)
  * [Data météo](#data-météo)
  * [Lib graphique en javascript](#lib-graphique-en-javascript)
<!-- /TOC -->

# Buts
Afficher, très facilement dans une page WEB, une représentation *graphique* de données fournies par une *API REST* en *json* ou fichiers textes.


# Problématiques
Comme cela doit rester très simple, moins d'une page de code, le code doit être *embarqué* dans le browser afin de ne pas avoir un serveur de plus à *gérer* dans ses services WEB


# Moyens
Pour cela on va utiliser les capacités de pouvoir faire tourner du *javascript* dans le browser et utiliser la libraire graphique *CanvasJS* pour la représentation graphique.

Tout devient alors vraiment très simple !


# Utilisation
Juste ouvrir dans son browser le fichier **index.html**



# Sources
## Data météo
https://www.prevision-meteo.ch/services/json/lausanne
https://www.prevision-meteo.ch/uploads/pdf/recuperation-donnees-meteo.pdf

## Lib graphique en javascript
https://canvasjs.com/docs/charts/basics-of-creating-html5-chart/
https://canvasjs.com/docs/charts/chart-types/
https://canvasjs.com/docs/charts/basics-of-creating-html5-chart/multi-series-charts/
https://canvasjs.com/docs/charts/intro/installation/





