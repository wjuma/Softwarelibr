## Suscripciones a telefonía celular móvil.

Crear una aplicación en NodeJS que permita leer los datos de las
Suscripciones a telefonía celular móvil, publicadas por el Banco
Mundial y publicar las estadísticas de un determinado país en un
año específico.

## Comenzando.

Esta instrucción permitira ejecutar la aplicación del proyecto en funcionamiento, para propósito de pruebas.

- Instalar el proyecto por medio de: https://github.com/ojimenezl/ProyectoPrimerParcialPW.git

### Pre-requisitos 📋

Para poder ejecutar la aplicación se requiere instalar el siguiente comando.

```html
npm i
```

### Ayuda

Este comando nos despliega unas opciones de ayuda para poder ejecutar la aplicación.

```html
node app guardar -help node app publicar -help
```

## Ejecutando las pruebas ⚙️

Al ingresar a la siguiente página: https://datos.bancomundial.org/indicador/IT.CEL.SETS
Esta nos indicara los años y paises disponibles para poder guiarse y hacer las consultas en nuestra aplicación.

Ejecutar una prueba de guardar. (Ejemplo)

- node app guardar -f ./modelo/API.csv -y 2017 -c KOR -o Hola

Ejecutar una prueba de publicar. (Ejemplo)

- node app publicar -f ./modelo/API.csv -y 2017 -c KOR

Por medio de este link se dirigira a la página web: http://localhost:3000

### Analice las pruebas end-to-end 🔩

- La media de suscripciones de todos los países en el año especificado.

```html
LA MEDIA DEL 2018 ES 308242982
```

- Establecer si el valor de las suscripciones del país
  determinado, es mayor o menor a la media mundial.

- Los cinco países por encima del valor de suscripciones del
  país determinado.

```html
TOP | AÑO | PAISES | SUSCRIPCIONES
```

```html
1 | 2018 | SEN | 16559942
```

```html
2 | 2018 | SYR | 17129676
```

```html
3 | 2018 | CMR | 18455836
```

```html
4 | 2018 | BFA | 19339109
```

```html
5 | 2018 | KHM | 19417123
```

- Los cinco países por debajo del valor de suscripciones del
  país determinado.

```html
TOP | AÑO | PAISES | SUSCRIPCIONES
```

```html
1 | 2018 | ZMB | 15470270
```

```html
2 | 2018 | YEM | 15297789
```

```html
3 | 2018 | TUN | 14769594
```

```html
4 | 2018 | MOZ | 14074248
```

```html
5 | 2018 | AGO | 13288421
```

- El top cinco de países para el año especificado.

```html
CODIGO | VALOR
```

```html
WLD | 7858266808
```

```html
IBT | 6400236446
```

```html
LMY | 6316274525
```

```html
MIC | 5970863639
```

```html
IBD | 5194063717
```

## Despliegue 📦

Agrega notas adicionales sobre como hacer deploy

## Construido con 🛠️

Las herramientas que utilizamos son:

- [Node.js]
- [Json]
- [HBS]
- [Html]

## Wiki 📖

Los recursos utilizados han sido los siguientes:

[Wiki](https://github.com/tu/proyecto/wiki)

## Autores ✒️

- _Nicolas Carrasco_
- _Oscar Jimenez_
- _Wendy Juma_ -
- _Eduardo Quisupangui_ -
- _Kevin Ramirez_ -
  También puedes mirar la lista de todos los [contribuyentes](https://github.com/ojimenezl/ProyectoPrimerParcialPW/graphs/contributors) quíenes han participado en este proyecto.

## Licencia 📄

Este proyecto está bajo la Licencia (Tu Licencia) - mira el archivo [LICENSE.md](LICENSE.md) para detalles

## Expresiones de Gratitud 🎁

- Comenta a otros sobre este proyecto 📢
- Invita una cerveza 🍺 o un café ☕ a alguien del equipo.
- Da las gracias públicamente 🤓.
- etc.

---

⌨️ con ❤️ por [Villanuevand](https://github.com/Villanuevand) 😊

```

```
