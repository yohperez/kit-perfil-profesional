# Kit Perfil Profesional 👔

Plantillas útiles para mejorar tu perfil profesional en GitHub, LinkedIn y otros espacios.

---

## 📋 Tabla de Contenidos

- [Descripción](#descripción)
- [🚀 Flujo de Trabajo](#-flujo-de-trabajo)
- [💡 Contribuir](#-contribuir)
- [🤝 Sugerencias para Colaboradores](#-sugerencias-para-colaboradores)
- [Licencia](#licencia)

---

## Descripción

Este repositorio contiene recursos y templates para optimizar tu presencia profesional en plataformas digitales. Encuentra plantillas de CV, perfiles LinkedIn, portafolios y más.

---

## 🚀 Flujo de Trabajo

Este proyecto usa un flujo de trabajo basado en **ramas y Pull Requests** para mantener el código limpio y seguro.

### Reglas Principales

✅ **main está protegida** - No se puede hacer push directo  
✅ **Todos los cambios requieren Pull Request** - Code review obligatorio  
✅ **Se requiere aprobación** - Mínimo 1 revisor  
✅ **Las ramas se limpian automáticamente** - Después de mergear  

### Pasos para Contribuir

#### 1️⃣ **Clonar el Repositorio**
```bash
git clone https://github.com/yohperez/kit-perfil-profesional.git
cd kit-perfil-profesional
```

#### 2️⃣ **Crear una Nueva Rama**
```bash
# Actualiza main primero
git checkout main
git pull origin main

# Crea una nueva rama con un nombre descriptivo
git checkout -b feature/descripcion-del-cambio
# o para fixes:
git checkout -b fix/descripcion-del-problema
```

**Nomenclatura de ramas recomendada:**
- `feature/nueva-funcionalidad` - Para nuevas características
- `fix/nombre-del-bug` - Para correcciones
- `docs/actualizacion-documentacion` - Para cambios en docs
- `refactor/mejora-codigo` - Para refactorización
- `style/cambios-css-o-diseño` - Para estilos

#### 3️⃣ **Hacer Cambios y Commits**
```bash
# Edita los archivos necesarios

# Verifica los cambios
git status

# Agrega los cambios
git add .

# Haz un commit con mensaje descriptivo
git commit -m "Descripción clara del cambio"

# Ejemplos de buenos mensajes:
# git commit -m "feat: agregar plantilla de CV en PDF"
# git commit -m "fix: corregir espaciado en sección de experiencia"
# git commit -m "docs: actualizar instrucciones de instalación"
```

#### 4️⃣ **Subir la Rama**
```bash
git push origin feature/descripcion-del-cambio
```

#### 5️⃣ **Crear un Pull Request**
- Ve a https://github.com/yohperez/kit-perfil-profesional
- Verás un botón **"Compare & pull request"**
- Completa la descripción del PR:
  - **Título:** Resumen claro del cambio
  - **Descripción:** Qué cambió y por qué (sé específico)
  - **Linked Issues:** Si está relacionado con algún issue

#### 6️⃣ **Code Review**
- Espera la aprobación de un revisor
- Responde a los comentarios de manera constructiva
- Haz los cambios solicitados en nuevos commits
- No fuerces los cambios (no uses `--force`)

#### 7️⃣ **Mergear a Main**
- Después de aprobación, haz click en **"Squash and merge"**
- Esto crea un commit limpio en main
- La rama se elimina automáticamente

#### 8️⃣ **Actualizar tu Local**
```bash
git checkout main
git pull origin main
```

---

### ⚠️ Lo que NO debes hacer

❌ Hacer push directo a `main` (GitHub lo bloqueará)  
❌ Hacer merge sin aprobación  
❌ Commitear en main localmente  
❌ Ignorar los comentarios en el code review  
❌ Hacer force push (`git push --force`)  
❌ Crear ramas sin nombre descriptivo  

---

### 💡 Ejemplo Completo

```bash
# 1. Actualizar main
git checkout main
git pull origin main

# 2. Crear rama
git checkout -b feature/agregar-plantilla-cv

# 3. Hacer cambios
# ... editas archivos ...

# 4. Commit
git add .
git commit -m "feat: agregar plantilla de CV en PDF"

# 5. Push
git push origin feature/agregar-plantilla-cv

# 6. Crear PR en GitHub y esperar aprobación
# 7. Mergear cuando esté aprobado
# 8. Actualizar main
git checkout main
git pull origin main
```

---

## 💡 Contribuir

### Para Colaboradores Internos

1. Crea tu rama directamente: `git checkout -b feature/mi-cambio`
2. Commit tus cambios: `git commit -m 'feat: descripción'`
3. Push a la rama: `git push origin feature/mi-cambio`
4. Abre un Pull Request en GitHub
5. Espera la revisión y aprobación

### Para Colaboradores Externos

1. **Fork** el repositorio
2. Crea tu rama en el fork: `git checkout -b feature/mi-cambio`
3. Commit y push en tu fork
4. Abre un Pull Request desde tu fork hacia main
5. Espera la revisión

---

## 🤝 Sugerencias para Colaboradores

Aquí hay algunas recomendaciones para asegurar una colaboración efectiva:

### 📌 Antes de Empezar

- ✅ Lee este README completamente
- ✅ Revisa los issues abiertos para no duplicar trabajo
- ✅ Comenta en un issue si quieres trabajar en él
- ✅ Verifica que tu rama esté actualizada con main

### 💬 Comunicación

- **Sé claro en los mensajes de commit**: Describe QUÉ y POR QUÉ, no solo QUÉ
- **En PRs, explica el contexto**: Ayuda al revisor a entender tu trabajo
- **Responde a los comentarios**: Valora el feedback del equipo
- **Sé respetuoso**: La colaboración es un diálogo constructivo

### 🎯 Buenas Prácticas

- **Commits pequeños**: Es más fácil revisar y entender
- **Una feature por PR**: No mezcles múltiples cambios en un mismo PR
- **Prueba tu código**: Asegúrate de que funcione antes de hacer push
- **No editees archivos sin necesidad**: Evita cambios cosméticos innecesarios
- **Actualiza tu rama**: Antes de hacer un PR, sincroniza con main

### 📝 Formato de Commits

Usa este formato para mensajes consistentes:

```
<tipo>: <descripción breve>

<descripción detallada si es necesario>

Cierra: #123 (si aplica)
```

**Tipos válidos:**
- `feat:` - Nueva funcionalidad
- `fix:` - Corrección de bug
- `docs:` - Cambios en documentación
- `style:` - Cambios de estilos (CSS, formato)
- `refactor:` - Refactorización sin cambiar funcionalidad
- `test:` - Agregar o actualizar tests
- `chore:` - Cambios en configuración o dependencias

**Ejemplos:**
```bash
git commit -m "feat: agregar plantilla de carta de presentación"
git commit -m "fix: corregir enlace roto en documentación"
git commit -m "docs: actualizar instrucciones de instalación"
git commit -m "style: mejorar espaciado en CV template"
```

### 🔄 Durante el Code Review

- **Sé receptivo**: Los comentarios no son crítica personal
- **Pregunta si no entiendes**: Mejor aclarar que asumir
- **Haz cambios en nuevos commits**: No hagas force push
- **Pide ayuda**: Si necesitas guidance, pregunta

### ✨ Tips para PRs Exitosos

1. **Tamaño moderado**: PRs muy grandes son difíciles de revisar
2. **Descripción clara**: Incluye qué, por qué y cómo
3. **Screenshots/demos**: Si es un cambio visual, muestra evidencia
4. **Checklist**: Verifica que todo funcione
5. **Paciencia**: Los revisores tienen otros compromisos

---

## 📋 Configuración de Protección de Main

Este repositorio tiene las siguientes protecciones activadas:

| Protección | Estado |
|-----------|--------|
| Require pull request reviews | ✅ 1 aprobación |
| Require status checks | ✅ (si aplica) |
| Require branches up to date | ✅ Sí |
| Auto-delete head branches | ✅ Sí |
| Squash merging enabled | ✅ Sí |
| Merge commits disabled | ✅ Deshabilitado |
| Rebase merging disabled | ✅ Deshabilitado |

---

## 🆘 Problemas Comunes

### "Error: permission denied to push to main"
```
✅ Solución: Estás en main y GitHub lo bloquea. Crea una rama primero.
```

### "Error: Your branch is behind origin/main"
```bash
✅ Solución: Actualiza tu rama
git fetch origin
git merge origin/main
# o para rebase:
git rebase origin/main
```

### "Quiero deshacer mi último commit"
```bash
✅ Solución (antes de hacer push):
git reset --soft HEAD~1  # Mantiene los cambios
git reset --hard HEAD~1  # Descarta los cambios
```

---

## 📚 Recursos Útiles

- [Git Documentation](https://git-scm.com/doc)
- [GitHub Flow Guide](https://guides.github.com/introduction/flow/)
- [Conventional Commits](https://www.conventionalcommits.org/)
- [GitHub Markdown Guide](https://guides.github.com/features/mastering-markdown/)

---

## Licencia

Este proyecto está bajo licencia MIT.

---

**¿Preguntas?** Abre un issue o contacta al equipo. ¡Feliz codificación! 🚀
