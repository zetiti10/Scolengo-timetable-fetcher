# Scolengo-timetable-fetcher

Une petite API permettant de récupérer l'emploi du temps de Scolengo sous forme de calendrier iCalendar.

Le programme est basé sur l'exemple [Hello world](https://expressjs.com/en/starter/hello-world.html).

## Déploiement

Cette API peut être déployée avec le service d'hébergement [Render](https://render.com). Pour cela, il suffit de renseigner l'url du dépot dans l'interface.

Dans l'onglet `Environment`, il faut renseigner la configuration obtenue avec le logiciel [Scolengo token](https://github.com/maelgangloff/scolengo-token) avec les variables suivantes :

| Variable                | Clé                 |
|-------------------------|---------------------|
| ACCESS_TOKEN            | access_token        |
| ID_TOKEN                | id_token            |
| REFRESH_TOKEN           | refresh_token       |
| TOKEN_TYPE              | token_type          |
| EXPIRES_AT              | expires_at          |
| SCOPE                   | scope               |
| ID                      | id                  |
| NAME                    | name                |
| ADDRESS_LINE_1          | addressLine1        |
| ADDRESS_LINE_2          | addressLine2        |
| ADDRESS_LINE_3          | addressLine3        |
| ZIP_CODE                | zipCode             |
| CITY                    | city                |
| COUNTRY                 | country             |
| HOME_PAGE_URL           | homePageUrl         |
| EMS_CODE                | emsCode             |
| EMS_OIDC_WELL_KNOWN_URL | emsOIDCWellKnownUrl |

En plus de cela, il est nécessaire de renseigner les variables `USERNAME` et `PASSWORD` pour sécuriser l'accès à l'agenda.

## Utilisation

Une fois le déploiement complété, il suffit d'appeler l'URL sous cette forme : `https://username:password@account.onrender.com/agenda` pour obtenir l'agenda.


This is the [Express](https://expressjs.com) [Hello world](https://expressjs.com/en/starter/hello-world.html) example on [Render](https://render.com).

The app in this repo is deployed at [https://express.onrender.com](https://express.onrender.com).