# Politique de confidentialité de ZOcre Control

Mise à jour le 15 novembre 2026. [English version](#zocre-control-privacy-policy)

## Responsable et périmètre

Gosse Nicolas est le responsable du traitement pour ZOcre Control, son service de vérification d’accès et l’assistance intégrée. Adresse de contact pour les données personnelles **zocrestudio@gmail.com**.

Lorsqu’un administrateur exploite un serveur nanos world, il détermine les traitements effectués pour sa propre communauté de joueurs. Cette politique décrit les traitements effectués par ZOcre dans le cadre de Control.

## Données et finalités

| Traitement | Données et provenance | Finalité et base légale |
| --- | --- | --- |
| Association et vérification Discord | Identifiant de compte, informations d’appartenance et de rôle obtenues auprès de Discord, justificatif de liaison, état de vérification et dates techniques | Gérer l’accès des membres aux téléchargements et opérations protégés, vérifier le droit d’accès sans refaire l’association à chaque opération. Intérêt légitime de ZOcre à contrôler cet accès et prévenir son détournement (article 6, paragraphe 1, point f du RGPD). |
| Sécurité du service d’accès | Adresse IP reçue lors de la connexion, opération demandée et informations techniques de session | Limiter les créations abusives de sessions, protéger la disponibilité et les accès. Intérêt légitime de sécurité du service (article 6, paragraphe 1, point f). |
| Assistance à la demande | Description envoyée, version, langue, informations techniques et diagnostics filtrés, fichiers choisis et référence de rapport | Examiner la demande et éviter les doublons d’envoi. Intérêt légitime de ZOcre à répondre aux demandes reçues et à diagnostiquer les incidents (article 6, paragraphe 1, point f). |

L’association Discord et le rôle Membre sont requis pour les opérations annoncées comme protégées. Ces fonctions sont indisponibles en l’absence de vérification. L’administration locale d’une installation standard déjà en place reste accessible selon les fonctions disponibles. Les rapports et leurs pièces jointes sont facultatifs.

## Destinataires et transferts

Le service d’accès et ses registres sont hébergés chez **OVHcloud**, qui fournit l’hébergement pour ZOcre. **Discord** fournit la vérification d’appartenance et héberge le canal privé qui reçoit les rapports soumis. Le contenu des rapports est réservé au support ZOcre. **GitHub** héberge la page et les fichiers de téléchargement publics. Lorsque tu demandes l’installation d’un serveur standard, **Valve** fournit SteamCMD et le serveur nanos world. Chacun de ces services reçoit les informations nécessaires aux connexions qui lui sont adressées. Pour leurs traitements propres, consulte les [conditions de confidentialité Discord](https://discord.com/privacy/policy/), la [politique GitHub](https://docs.github.com/fr/site-policy/privacy-policies/github-general-privacy-statement), la [politique OVHcloud](https://www.ovhcloud.com/fr/terms-and-conditions/privacy-policy/) et la [politique Valve](https://store.steampowered.com/privacy_agreement/).

Discord et GitHub indiquent que leurs services impliquent des traitements hors de l’Espace économique européen, notamment aux États-Unis. Leurs politiques décrivent les mécanismes utilisés pour leurs propres traitements. Les [conditions développeur Discord](https://support-dev.discord.com/hc/en-us/articles/8562894815383-Discord-Developer-Terms-of-Service) prévoient aussi des clauses contractuelles types pour les transferts de données Discord relevant de leur section 11. Les garanties d’hébergement sont décrites dans l’[annexe de protection des données OVHcloud](https://contract.eu.ovhapis.com/1.0/pdf/OVH_Data_Protection_Agreement-fr.pdf). Tu peux demander à ZOcre des précisions sur les garanties applicables et une copie de ces garanties lorsqu’elles peuvent être communiquées.

## Conservation et sécurité

- Le service utilise l’IP pour limiter le nombre de créations de session sur une fenêtre d’une minute. Les sessions et autorisations courtes ont une échéance en minutes.
- Le justificatif de liaison est conservé localement dans un stockage chiffré lié au compte Windows. Sur le service, la liaison expire après 180 jours d’inactivité. L’expiration révoque l’accès. Une liaison expirée peut rester dans le registre jusqu’à son retrait. À la dissociation, le service révoque le justificatif puis retire l’identifiant Discord et les dates de liaison du registre actif. Il conserve l’empreinte du justificatif révoqué pour empêcher sa réactivation lors d’une restauration. Des copies antérieures peuvent subsister dans les sauvegardes jusqu’à leur rotation par nombre de copies.
- Les archives de journaux du bot sont soumises à la rotation configurée par le service. Les rapports, diagnostics et fichiers transmis restent dans le canal privé du support jusqu’à leur suppression. Le registre anti-doublon conserve des références, empreintes techniques, dates et états d’envoi. La version actuelle ne prévoit pas d’effacement automatique de ce registre ni des rapports Discord.
- ZOcre utilise la vérification d’accès aux opérations protégées, des connexions HTTPS et les contrôles d’accès du canal support. La dissociation est disponible dans les fonctions de liaison de compte. Tu peux demander l’effacement des données auprès du contact indiqué ci-dessus.

## Tes droits

Tu peux demander l’accès à tes données, leur rectification, leur effacement ou la limitation du traitement, et t’opposer à un traitement fondé sur l’intérêt légitime. La portabilité s’applique lorsque ses conditions légales sont remplies. Écris à **zocrestudio@gmail.com** en précisant la demande et, si tu l’as, la référence du rapport. Tu peux aussi adresser une [réclamation à la CNIL](https://www.cnil.fr/fr/adresser-une-plainte).

# ZOcre Control Privacy Policy

Updated on 15 November 2026.

## Controller and scope

Gosse Nicolas is the controller for ZOcre Control, its access verification service and built-in support. For privacy requests, contact **zocrestudio@gmail.com**.

Administrators who operate nanos world servers determine the processing for their own player communities. This policy covers the processing carried out by ZOcre for Control.

## Data and purposes

| Processing | Data and source | Purpose and legal basis |
| --- | --- | --- |
| Discord account linking and verification | Account ID, membership and role information from Discord, link credential, verification status and technical timestamps | Manage member access to protected downloads and operations. ZOcre's legitimate interest in controlling and protecting access (Article 6(1)(f) GDPR). |
| Access service security | IP address received on connection, action requested and technical session information | Rate-limit abusive session creation and protect availability and access. Legitimate interest in securing the service (Article 6(1)(f)). |
| Support on request | Description sent, version, language, technical information and filtered diagnostics, selected attachments and report reference | Review the request and prevent duplicate submissions. Legitimate interest in responding to requests and diagnosing issues (Article 6(1)(f)). |

A linked Discord account and verified Member role are required for operations marked as protected. These operations are unavailable without verification. Local administration of an existing standard server remains available according to the available features. Sending reports and attachments is optional.

## Recipients and transfers

**OVHcloud** provides hosting for the access service and its records. **Discord** provides membership verification and hosts the private channel where submitted reports are received. Report content is restricted to ZOcre support. **GitHub** hosts the public download page and files. **Valve** provides SteamCMD and the nanos world server when a standard server installation is requested. Each service receives the information necessary for connections made to it. For their own processing, see the [Discord privacy policy](https://discord.com/privacy/policy/), [GitHub privacy statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement), [OVHcloud privacy policy](https://www.ovhcloud.com/en/terms-and-conditions/privacy-policy/) and [Valve privacy policy](https://store.steampowered.com/privacy_agreement/).

Discord and GitHub describe processing outside the European Economic Area, including in the United States, and explain the mechanisms for their own processing. The [Discord Developer Terms](https://support-dev.discord.com/hc/en-us/articles/8562894815383-Discord-Developer-Terms-of-Service) also provide standard contractual clauses for Discord data transfers covered by section 11. Hosting safeguards are described in the [OVHcloud Data Protection Agreement](https://contract.eu.ovhapis.com/1.0/pdf/OVH_Data_Protection_Agreement-fr.pdf). Contact ZOcre for information about applicable safeguards and a copy where available.

## Retention and security

- The access service uses IP addresses to rate-limit session creation over a one-minute window. Short-lived sessions and authorisations expire within minutes.
- The link credential is kept in encrypted storage linked to the Windows account. Server-side links expire after 180 days of inactivity. Expiry revokes access. An expired link may remain in the records until it is removed. When you unlink, the service revokes the credential and then removes the Discord ID and link timestamps from the active records. It retains a hash of the revoked credential to prevent reactivation after a restore. Older copies may remain in backups until they rotate by copy count.
- Bot log archives are subject to the service's configured rotation. Submitted reports, diagnostics and files remain in the private support channel until removed. The duplicate-prevention records contain references, technical hashes, dates and delivery states. The current service does not automatically delete those records or the Discord reports.
- ZOcre uses access checks for protected operations, HTTPS connections and access controls on the support channel. You can unlink your account through the account-linking controls. You can request deletion using the contact above.

## Your rights

You may request access, rectification, erasure or restriction of processing, and you may object to processing based on legitimate interests. You may request portability where its legal requirements are met. Email **zocrestudio@gmail.com** with details of your request and the report reference if available. You may also [lodge a complaint with the CNIL](https://www.cnil.fr/fr/adresser-une-plainte).
