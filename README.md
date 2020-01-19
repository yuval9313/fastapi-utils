<p align="center">
    <em>Reusable utilities for FastAPI</em>
</p>


---

**Documentation**: <a href="https://fastapi-utils.davidmontague.xyz" target="_blank">https://fastapi-utils.davidmontague.xyz</a>

**Source Code**: <a href="https://github.com/dmontagu/fastapi-utils" target="_blank">https://github.com/dmontagu/fastapi-utils</a>

---

<a href="https://fastapi.tiangolo.com">FastAPI</a> is a modern, fast web framework for building APIs with Python 3.6+.

But if you're here, you probably already knew that!

---

## Features

This package includes a number of utilities to help reduce boilerplate and reuse common functionality across projects:

* **Class Based Views**: Stop repeating the same dependencies over and over in the signature of related endpoints.
* **Response-Model Inferring Router**: Let FastAPI infer the `response_model` to use based on your return type annotation. 
* **Repeated Tasks**: Easily trigger periodic tasks on server startup
* **Timing Middleware**: Log basic timing information for every request
* **SQLAlchemy Sessions**: The `FastAPISessionMaker` class provides an easily-customized SQLAlchemy Session dependency
* **GUID Type**: The provided GUID type makes it easy to use UUIDs as the primary keys for your database tables 

---

It also adds a variety of more basic utilities that are useful across a wide variety of projects:

* **APIModel**: A reusable `pydantic.BaseModel`-derived base class with useful defaults
* **APISettings**: A subclass of `pydantic.BaseSettings` that makes it easy to configure FastAPI through environment variables 
* **String-Valued Enums**: The `StrEnum` and `CamelStrEnum` classes make string-valued enums easier to maintain
* **CamelCase Conversions**: Convenience functions for converting strings from `snake_case` to `camelCase` or `PascalCase` and back
* **OpenAPI Spec Simplification**: Simplify your OpenAPI Operation IDs for cleaner output from OpenAPI Generator

See the [docs](index.md) for more details and examples. 

## Requirements

This package is intended for use with any recent version of FastAPI (depending on `pydantic>=1.0`), and Python 3.6+.

## Installation

```bash
pip install fastapi-utils
```

## License

This project is licensed under the terms of the MIT license.
