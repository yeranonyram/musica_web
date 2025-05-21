# 🎵 Ritmo Vivo - Sitio Web de Música

Este es un proyecto web desarrollado en HTML puro.

---

## 📁 Estructura de Archivos

- `index.html` – Página principal
- `sobre.html` – Información sobre la escuela
- `conciertos.html` – Eventos y conciertos
- `galeria.html` – Galería de imágenes
- `contacto.html` – Formulario de contacto

---

## 🚀 Control de Versiones con Git y GitHub

- ✅ Repositorio inicializado con `git init`
- 🔀 Trabajo organizado con ramas:
  - `main` – rama principal de producción
  - `develop` – rama de integración
  - `feature/nav` – barra de navegación
  - `feature/contenido` – contenido principal
  - `feature/galeria` – galería de imágenes
  - `feature/contacto` – página de contacto
- 💡 Más de **10 commits** agrupados de forma lógica
- 🏷️ Tag creado: `v1.0.0` (versión final estable)

---

## 🧪 Pasos Realizados en Git

```bash
# Inicialización del proyecto
git init
git add .
git commit -m "feat: estructura inicial con 5 archivos HTML"

# Ramas de desarrollo
git branch develop
git switch debelop
git branch feature/nav
# desarrollos...
git add .
git commit -m "feat(nav): navbar creada en todas las páginas"

git brach feature/contenido
# desarrollos...
git commit -m "feat(contenido): secciones principales agregadas"
git switch develop
git merge feature/contenido

git brach feature/galeria
# desarrollos...
git commit -m "feat(galeria): se agregó galería de imágenes"
git switch develop
git merge feature/galeria

git brach feature/contacto
# desarrollos...
git commit -m "feat(contacto): se agregó formulario de contacto"
git switch develop
git merge feature/contacto

# Integración final
git switch main
git merge develop

# Tag de versión final
git tag -a v1.0.0 -m "Versión final del proyecto de música web Yerko Flores"
git push origin v1.0.0

