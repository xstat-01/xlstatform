# xstatForm

Formulaire web de collecte de données destiné au coordinateur des Jeunes Volontaires Agricoles (JVA) du département de Bambey, dans le cadre du bilan de la campagne agricole 2025/2026.

---

## Fonctionnalités

- Saisie guidée en 2 étapes (Identité & Paiement)
- Calcul automatique du montant total perçu (50 000 / 100 000 FCFA)
- Envoi des données par email via Formspree
- Compatible mobile (téléphone des JVA)
- Déployé et accessible via lien partageable WhatsApp

## Technologies

- HTML / CSS / JavaScript (vanilla)
- [Formspree](https://formspree.io) — collecte et transmission des soumissions par email
- [Github](https://xstat-01.github.io/xlstatform/) — hébergement et déploiement continu

## Structure du projet

```
xstatForm/
└── index.html        # Formulaire principal (toute l'application)
└── README.md         # Documentation du projet
```

## Utilisation

1. Le coordinateur partage le lien du formulaire aux JVA via WhatsApp
2. Chaque JVA remplit le formulaire en 2 étapes depuis son téléphone
3. À la soumission, les données sont transmises automatiquement au coordinateur par email
4. Le coordinateur compile les données pour le bilan de campagne

## Données collectées

| Section | Champs |
|---|---|
| Identité | Prénom, Nom, Téléphone, Email, N° CNI, Date de prise de service, Commune, Superviseur |
| Paiement | Téléphone Wave/OM, Opérateur, Nb paiements 50 000 FCFA, Nb paiements 100 000 FCFA |

## Déploiement

Site déployé sur Github :
[[https://xstat-01.github.io/xlstatform/](https://xstat-01.github.io/xlstatform/)]

> Tout push sur la branche `main` déclenche un redéploiement automatique sur Netlify.

## Auteur

Coordinateur JVA — Département de Bambey
ANCAR — Agence Nationale de Conseil Agricole et Rural
Campagne agricole 2025/2026
