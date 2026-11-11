# El Mehdi Youssef Baggar

Étudiant ingénieur en dernière année à **EFREI Paris**, spécialité **Cybersécurité & Cloud** (diplôme 2027).

Je recherche un **stage de fin d'études de 6 mois à partir de mars 2027**.

---

## Expérience

**Stage administration systèmes et réseaux** — Canal Informatique (Maroc), déc. 2025 – avr. 2026
- Windows Server et Active Directory : comptes, groupes de sécurité, permissions, contrôle des accès
- Réseau : TCP/IP, DNS, DHCP, diagnostic et résolution d'incidents
- Maintenance, supervision et sauvegardes

## Projets

### Infrastructure et réseau

**AGROMECA — SI d'entreprise virtualisé et sécurisé** (projet de groupe EFREI)
Déploiement complet sur VMware ESXi : segmentation par zones (IT, identité, serveurs, DMZ, supervision), pfSense/OPNsense, VLAN, VPN, messagerie, supervision.
Ma partie :
- **Active Directory** : domaine, DNS, OU, utilisateurs et groupes, intégration des postes
- **GPO** : stratégies de sécurité et restrictions liées aux OU
- **PKI Microsoft** : Root CA → Subordinate CA, CSR, signature, révocation, certificats TLS des services internes

**Sécurité réseau d'une ONG multi-sites** (projet EFREI — Sécurité des réseaux)
Infrastructure sécurisée sous **pfSense** entre un siège (Paris) et une antenne (Madrid) : VPN site-à-site, VPN d'accès distant pour le personnel, serveur web en HTTPS uniquement, DNS primaire et cache séparés en deux vues. Livrables : plan d'adressage, fichiers de configuration, plan de tests et vidéo de démonstration.

### Sécurité Active Directory et tests d'intrusion

**Infrastructure Active Directory vulnérable — build & break** (projet EFREI)
Déploiement d'un domaine AD (contrôleur de domaine, utilisateurs, groupes à privilèges, GPO) volontairement configuré avec des vulnérabilités réalistes, puis exploitation dans une chaîne d'attaque démontrée en live, de l'énumération à l'élévation de privilèges. Double rôle : administrateur puis attaquant.

**Audit de sécurité Active Directory, pentest et CTF** (projet de groupe EFREI)
Contrôleur de domaine peuplé et fragilisé avec BadBlood, intégration d'un serveur membre, script PowerShell de création d'objets AD. Audit de l'annuaire (PingCastle, BloodHound), cassage de mot de passe par dictionnaire avec **John the Ripper** sur un compte du domaine depuis Kali, recherche de flags, et réflexion sur la gouvernance SSI appliquée à l'AD.

**Test d'intrusion en 5 phases** (projet EFREI — Ethical Hacking)
Mission simulée de consultant sur une entreprise fictive : reconnaissance passive et active, scan et énumération, exploitation, persistance et effacement des traces, avec rapport documenté (commandes, captures, vulnérabilités et recommandations) et soutenance.

### Cloud

**PowerView — architecture cloud de supervision énergétique** (projet EFREI — Cloud Architecture)
Conception d'une plateforme sur **AWS** collectant la télémétrie de 1 600 PDU de datacenter pour une filiale d'un groupe financier : collecteur on-premise en DMZ, lien hybride privé, pipeline d'ingestion et de stockage, KPI, portail multi-tenant avec isolation stricte des données, alerting. Points traités : moindre privilège, résidence des données en UE, journaux d'audit infalsifiables, scénarios de panne et design patterns cloud.

### Autres

**Cyber range personnel** *(en cours)*
Laboratoire sur VMware Workstation pour pratiquer l'attaque et la défense dans un environnement autorisé : pfSense/OPNsense, plusieurs sous-réseaux, Windows Server + AD, client Windows, Linux, Kali. Côté défense : Wazuh, Sysmon et collecte de journaux pour la détection.

**Plateforme de covoiturage** (projet web)
Vue.js, Node.js, MySQL. Authentification, réservations, et sécurité applicative : hachage bcrypt, contrôle d'accès, validation des entrées, sessions.

## Compétences

- **Réseaux** : TCP/IP, subnetting, VLAN, routage, DNS, DHCP, NAT, ACL, VPN, Cisco Packet Tracer, Wireshark
- **Systèmes** : Windows Server, Active Directory, GPO, Linux (Ubuntu, Kali), Bash, SSH
- **Sécurité** : PKI / TLS, segmentation, VPN, SIEM (Splunk, Wazuh), Sysmon, MITRE ATT&CK
- **Pentest (labos)** : Nmap, Metasploit, BloodHound, PingCastle, Hashcat, John the Ripper, attaques Kerberos (Kerberoasting, AS-REP Roasting)
- **Cloud** : AWS (EC2, VPC, IAM), Azure / Microsoft Entra ID (en cours d'apprentissage)
- **Langages** : Python, Bash, C, Java, JavaScript, SQL

## Langues

Français courant · Anglais professionnel · Arabe langue maternelle

---

Me contacter : via [LinkedIn](https://www.linkedin.com/in/el-mehdi-youssef-baggar-0865b5316)
