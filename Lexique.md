 -- Lexique Code --

 // API (Application Programming Interface) //

        Ensemble de règles permettant à deux applications de communiquer entre elles
        Le front-end React envoie une requête à l'API Spring Boot pour récupérer la liste des utilisateurs

*****

// Backend //

        Partie utilitaire de l'application
        Elle contient la logique métier, les traitements et l'accès à la base de données
               - Spring Boot

*****

// Frontend //

        Partie graphique de l'application utilisée par les utilisateurs
               - React, HTML, CSS, JavaScript

*****

// Base de données (Database) //

        Endroit où les données sont stockées de manière permanente      
               - PostgreSQL, MySQL

*****

// ORM (Object Relational Mapping) //

        Technique permettant de manipuler une base de données avec des objets Java au lieu d'écrire directement du SQL
               - Hibernate, JPA

*****

// JPA (Java Persistence API) //

        Spécification Java définissant comment utiliser un ORM
        JPA définit les règles
        Hibernate est l'implémentation la plus utilisée

*****

// Hibernate //

        Implémentation de JPA
        Il transforme automatiquement les objets Java en requêtes SQL

*****

// Entity //

        Classe Java représentant une table de la base de données

*****

// DTO (Data Transfer Object) //

        Objet servant uniquement à transporter des données entre le client et le serveur

*****

// Mapper //

        Classe qui convertit une Entity en DTO et inversement
                Entity <- -> Mapper <- -> DTO

*****

// Controller //

        Point d'entrée de l'API
        Il reçoit les requêtes HTTP du client

*****

// REST API //

        API utilisant le protocole HTTP

*****

// JWT (JSON Web Token) //

        Jeton d'authentification permettant d'identifier un utilisateur sans stocker de session côté serveur

*****

// Authentification //

        Vérifie l'identité d'un utilisateur

*****

// Hash //

        Transformation irréversible d'un mot de passe

*****

// JSON (JavaScript Object Notation) //

        Format d'échange de données

*****

// HTTP //

        Protocole utilisé pour communiquer entre un client et un serveur

*****

// Maven //

        Outil de gestion des dépendances Java (pom.xml)

*****

// Dependency //

        Bibliothèque externe ajoutée au projet
               - Spring Web, Spring Data JPA

*****

// Docker //   

        Logiciel permettant d'exécuter une application dans un conteneur

*****

// Container //

        Environnement isolé contenant une application et toutes ses dépendances

*****

// PostgreSQL //

        Système de gestion de base de données relationnelle

*****

// SQL //

        Langage permettant d'interagir avec une base de données

*****

// NoSQL (Not Only SQL) //

        Famille de bases de données qui ne stockent pas forcément les données sous forme de tables
        Elles sont souvent utilisées lorsque les données sont très volumineuses ou peu structurées
        Contrairement au SQL, les données peuvent être stockées sous forme de documents, de clés/valeurs, de graphes ou de colonnes
               - MongoDB

*****

// Foreign Key (Clé étrangère) //

        Lien entre deux tables

*****

// Primary Key (Clé primaire) //

        Identifiant unique d'une ligne dans une table

*****

// CRUD //

        Les quatre opérations principales sur les données
                Create - Read - Update - Delete

*****

// Endpoint //

        URL exposée par une API (GET /users)

*****

// Framework //

        Ensemble d'outils facilitant le développement
               - Springboot, React

*****

// Bibliothèque (Library) //

        Code réutilisable ajouté dans un projet

*****

// Injection de dépendances (Dependency Injection) //

        Technique permettant à Spring de créer automatiquement les objets nécessaires

*****

// Annotation //

        Instruction précédée d'un `@` donnant un comportement particulier à une classe ou une méthode

*****

// Spring Boot //

        Framework Java permettant de créer rapidement des applications et des API

*****

// IDE (Integrated Development Environment) //

        Logiciel regroupant tous les outils nécessaires pour développer une application

*********************************************************************************************************
*********************************************************************************************************

// Variable //

        Emplacement mémoire permettant de stocker une valeur
        Une variable peut contenir différents types de données selon son type
        Une variable peut être locale (dans une méthode) ou appartenir à un objet (on parle alors d'attribut)

*****

// Attribut //

        Variable appartenant à une classe ou à un objet
        Les attributs représentent les caractéristiques d'un objet

*****

// Classe //

        Modèle servant à créer des objets
        Une classe définit les attributs (les données) et les méthodes (les comportements)

*****

// Méthode //

        Fonction appartenant à une classe
        Une méthode décrit une action que peut réaliser un objet
        Une méthode peut recevoir des paramètres - retourner une valeur - ne rien retourner (void)

*****

// Type //

        Détermine la nature des données qu'une variable peut contenir
        Types primitifs : int - double - float - boolean - char - byte - short - long
        Types objets : String - User - List<User> - LocalDate

*****

// Objet // 

        Élément créé à partir d'une classe Un objet possède des attributs et peut utiliser les méthodes définies dans sa classe 
        
*****

// Instance // 

        Objet concret créé à partir d'une classe

***** 

// Instanciation // 

        Action de créer un objet à partir d'une classe

***** 

// Constructeur // 

        Méthode spéciale appelée lors de la création d'un objet Il permet d'initialiser les attributs de l'objet

*****

// Paramètre // 

        Variable déclarée dans la définition d'une méthode

*****

// Argument // 

        Valeur transmise à une méthode lors de son appel

*****

// Valeur de retour // 

        Résultat renvoyé par une méthode grâce au mot-clé return

***** 
// Interface // 

        Contrat définissant les méthodes qu'une classe doit implémenter Une interface décrit ce qui doit être fait, sans forcément préciser comment

***** 

// Implémentation // 

        Code concret permettant de réaliser le comportement défini par une interface 

 ***** 

// Héritage //

        Mécanisme permettant à une classe de récupérer les attributs et méthodes d'une autre classe 

***** 

// Encapsulation // 

        Principe consistant à protéger les données d'un objet et à contrôler leur accès

***** 

// Polymorphisme // 

        Capacité à utiliser plusieurs objets différents à travers un même type commun 

***** 

// Abstraction // 

        Principe consistant à masquer les détails complexes pour ne montrer que les éléments nécessaires

***** 

// Enum // 

        Type contenant une liste limitée de valeurs possibles

 ***** 

 // Compilation // 

        Transformation du code source en code compréhensible et exécutable par la machine ou la JVM 

 ***** 
 
 // Compilateur // 

        Programme chargé de vérifier et de compiler le code source 

 ***** 

 // JVM (Java Virtual Machine) // 
 
        Environnement permettant d'exécuter du code Java sur différents systèmes d'exploitation 

 ***** 
 // JDK (Java Development Kit) // 
 
        Ensemble des outils nécessaires pour développer et compiler des applications Java

 ***** 

 // JRE (Java Runtime Environment) // 
 
        Environnement nécessaire pour exécuter une application Java 

 ***** 

 // Débogage (Debug) // 

         Processus permettant de rechercher et corriger les erreurs dans un programme

*****

// Relation One-to-One // 

        Relation dans laquelle un élément correspond à un seul autre élément 
        
***** 
// Relation One-to-Many // 

        Relation dans laquelle un élément peut être associé à plusieurs autres éléments 
        
***** 
// Relation Many-to-One // 

        Relation dans laquelle plusieurs éléments peuvent être associés à un seul élément 

***** 
// Relation Many-to-Many // 

        Relation dans laquelle plusieurs éléments peuvent être associés à plusieurs autres éléments 

***** 
// Table //    

        Structure d'une base de données relationnelle contenant des lignes et des colonnes