# Proyecto WEB

Base de React + Vite con JavaScript.

## Desarrollo local

En PowerShell, instala las dependencias y arranca Vite.

```powershell
npm.cmd ci
npm.cmd run dev
```

Usa `npm.cmd run build` para compilar y `npm.cmd run lint` para revisar el código.

## GitFlow

- `main` conserva las versiones estables.
- `develop` integra el trabajo de desarrollo.
- `feature/*` y `release/*` parten de `develop`.
- `hotfix/*` parte de `main` para correcciones urgentes.
