# Introducción a Angular

Introducción a Angular version 14.2.2.

## Secciones vistas

1. Generar un proyecto en Angular.
2. Explicación de cada archivo del proyecto.
3. ¿Qué es el App Component?
4. Generación de un Component llamado "Contador".
5. Temas vistos en este tutorial.

## Generar un proyecto en Angular

Se puede descargar este proyecto directamente desde este repositorio o ejecutar la siguiente sentencia en consola dentro de la carpeta a utilizar para el proyecto `ng new 01-bases`

## Explicación de cada archivo del proyecto.

Archivo `tsconfig.json`: Archivo de configuración de TypeScript.

Archivo `tsconfig.spec.json`: Archivo de configuración de TypeScript, extendido de `tsconfig.json`.

Archivo `tsconfig.app.json`: Archivo de configuración de TypeScript, extendido de `tsconfig.json`.

Archivo `README.md`: Archivo de texto, con códigos, títulos, para dar descripciones del proyecto.

Archivo `package.json`: Archivo delicado, se recomienda no hacer modificaciones manuales. Archivo para agregar dependencias se puede utilizar comandos que se verán más adelante.

Archivo `package-lock.json`: Archivo que explica como se construyó el proyecto y sus módulos.

Archivo `karma.conf.js`: Archivo que configuración para las pruebas unitarias y de integración del proyecto.

Archivo `angular.json`: Archivo que contiene configuraciones del proyecto, como favicon, assets, styles entre otros.

Archivo `.gitignore`: Archivo que indica los archivos que no se quiere subir mediante Git.

Directorio `node_modules/`: Paquetes instalados para Angular y su desarrollo.

Directorio `src/`: Dentro de esta carpeta se encuentra lo siguiente:

* `app/`: Contiene los archivos para la raiz del proyecto.
* `assets/`: Contiene los archivos y recursos estáticos, por ejemplo: imágenes, sonidos, etc.
* `environments/`: Contiene los archivos para indicarle a Angular las variables de entorno, ya sea de desarrollo y producción.

| Archivo            | Descripción                                                              |
|--------------------|--------------------------------------------------------------------------|
| app.component.css  | Archivo que hace relación al estilo que se aplicará al componente "app". |
| app.component.html | Archivo que contiene el código HTML del componente "app".                |
| app.component.ts   | Archivo que contiene la clase de Typescript del componente "app".        |
| app.module.ts      | Archivo que contiene la clase de Typescript del módulo "app".            |

## ¿Qué es el App Component?

Es la raíz del proyecto, en donde, si se visualiza el archivo `src/index.html`, se encontrará la marca `<app-root></app-root>`.

## Generación de un Component llamado "Contador"

Ejecutar la sentencia en consola `ng g c contador`.

## Temas vistos en este tutorial

* Generación de módulos.
* Generación de componentes.
* Concepto de "one way data binding".
* Directiva *ngFor.
* Directiva *ngIf.
* Directivas Ng-Template y ngIf-else.

Curso seguido del master [Fernando Herrera](https://twitter.com/fernando_her85) de [Udemy](https://www.udemy.com/course/angular-fernando-herrera/)
