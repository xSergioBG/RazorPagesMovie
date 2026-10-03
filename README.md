# Razor Pages Movie

Ejemplo web con ASP.NET Core Razor Pages y Entity Framework Core para SQL Server.

## Requisitos

- SDK de .NET 8, según el proyecto.
- SQL Server accesible y una cadena de conexión de desarrollo.

## Ejecutar

```sh
git clone https://github.com/xSergioBG/RazorPagesMovie.git
cd RazorPagesMovie
dotnet restore RazorPagesMovie.sln
dotnet build RazorPagesMovie.sln
dotnet run --project RazorPagesMovie
```

Revisa la configuración de la aplicación y las migraciones antes de conectarla a una base de datos. Guarda las credenciales reales en configuración local o secretos de usuario.

## Estructura

- [RazorPagesMovie.sln](RazorPagesMovie.sln): solución.
- [RazorPagesMovie/](RazorPagesMovie/): aplicación Razor Pages, modelo y configuración.

El manifiesto declara .NET 8 y paquetes EF Core 8. Esta documentación identifica el entorno del repositorio; no acredita un despliegue ni una conexión a base de datos probada.
