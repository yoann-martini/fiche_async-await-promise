# fiche_async-await-promise
Description des technologies sync, await, promise

Sync await permet d'attendre que les instructions soient réalisées en parallèle pendant que l'application continue à tourner.
Si les instructions fonctionnnent alors elles sont retournées sous forme de valeur.
Si les instructions ne fonctionnent pas une erreur est retournée.

Promise fonctionne comme Sync await, c'est un composant qui englobe un code qui prend plus de temps.

exemple : 

let promise = new Promise(function(resolve, reject) {
  // executor (the producing code)
});

Les paramètres resolve et reject sont des callbacksde javascript. Notre code est au niveau de l'executor (dans l'exemple du haut). 
