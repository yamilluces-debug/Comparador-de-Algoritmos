# Comparador de Algoritmos de Caminos Mínimos

## Descripción del Proyecto

Este proyecto consiste en una aplicación desarrollada en **Java** que permite generar, visualizar y analizar grafos, así como comparar el rendimiento de dos algoritmos clásicos de búsqueda de caminos mínimos:

* **Dijkstra**
* **Bellman-Ford**

La aplicación permite al usuario crear grafos manualmente o generarlos automáticamente, visualizar su estructura y ejecutar ambos algoritmos para calcular las rutas más cortas desde un nodo origen hacia los demás nodos del grafo.

Además, el sistema mide el **tiempo de ejecución de cada algoritmo** y presenta los resultados en una **tabla comparativa**, lo que permite observar de manera clara las diferencias de rendimiento entre ambos métodos.

Este proyecto tiene un enfoque **educativo y académico**, orientado a comprender el funcionamiento de los algoritmos de grafos y su comportamiento en distintos escenarios.

---

# Funcionalidades Principales

La aplicación incluye las siguientes características:

* Creación de grafos mediante **entrada manual de aristas**.
* **Generación automática de grafos** para pruebas.
* **Visualización gráfica del grafo** mediante nodos y aristas.
* Ejecución del algoritmo **Dijkstra**.
* Ejecución del algoritmo **Bellman-Ford**.
* Cálculo del **camino mínimo desde un nodo origen**.
* Medición del **tiempo de ejecución de cada algoritmo**.
* **Comparación de resultados** en una tabla.
* Representación visual del grafo dentro de la interfaz.

---

# Tecnologías Utilizadas

* **Lenguaje:** Java (JDK 11)
* **Interfaz gráfica:** Java Swing
* **Gráficos:** Java AWT / Graphics2D
* **IDE recomendado:** Apache NetBeans 8.2
* **Control de versiones:** Git
* **Repositorio:** GitHub

---

# Arquitectura del Proyecto

El proyecto sigue una **arquitectura modular**, separando las responsabilidades del sistema en diferentes paquetes para facilitar el mantenimiento y la organización del código.

```
src
│
├── main
│   └── Main.java
│
├── modelo
│   ├── Nodo.java
│   ├── Arista.java
│   └── Grafo.java
│
├── algoritmos
│   ├── Dijkstra.java
│   └── BellmanFord.java
│
├── comparador
│   └── ComparadorAlgoritmos.java
│
└── interfaz
    ├── InterfazGrafica.java
    └── PanelGrafo.java
```

### Descripción de los módulos

**modelo**

Contiene las clases que representan la estructura del grafo:

* Nodo
* Arista
* Grafo

**algoritmos**

Incluye las implementaciones de los algoritmos de caminos mínimos:

* Dijkstra
* Bellman-Ford

**comparador**

Permite ejecutar ambos algoritmos y medir su tiempo de ejecución para realizar la comparación.

**interfaz**

Contiene la interfaz gráfica del programa y el panel encargado de dibujar los grafos.

**main**

Clase principal que inicia la aplicación.

---

# Formato de Entrada del Grafo

El programa permite ingresar aristas utilizando el siguiente formato:

```
Origen Destino Peso
```

Ejemplo:

```
A B 4
A C 2
C B 1
B D 5
```

Cada línea representa una **arista del grafo con su peso**.

---

# Instalación

Para ejecutar el proyecto necesitas:

* **Java JDK 11 o superior**
* **Apache NetBeans 8.2** (recomendado) o cualquier IDE compatible con Java

## 1. Clonar el repositorio

```
git clone https://github.com/tu-usuario/tu-repositorio.git
```

## 2. Abrir el proyecto

1. Abrir **Apache NetBeans**
2. Seleccionar:

```
File → Open Project
```

3. Buscar la carpeta del proyecto descargado
4. Abrir el proyecto

---

# Ejecución del Programa

Una vez abierto el proyecto en NetBeans:

1. Localizar la clase principal:

```
Main.java
```

2. Ejecutar el proyecto presionando:

```
Run Project
```

o usando la tecla:

```
F6
```

3. La **interfaz gráfica se abrirá automáticamente**.

---

# Uso del Programa

Dentro de la interfaz podrás:

1. **Ingresar un grafo manualmente**.
2. **Generar un grafo automáticamente**.
3. **Ejecutar los algoritmos de caminos mínimos**.
4. Visualizar el **grafo generado**.
5. Comparar el **tiempo de ejecución de los algoritmos**.

---

# Objetivo Académico

Este proyecto fue desarrollado con fines académicos para:

* Analizar el comportamiento de **algoritmos de caminos mínimos**.
* Aplicar conceptos de **estructuras de datos y grafos**.
* Practicar **programación orientada a objetos en Java**.
* Desarrollar **interfaces gráficas con Java Swing**.

---

# Autor

Proyecto desarrollado como parte de un trabajo académico relacionado con el análisis y comparación de algoritmos en grafos.

---
