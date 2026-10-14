# tiny-router

A very small path router with named parameters and method matching.

## Why

The existing libraries were either abandoned or pulled in a large dependency tree.

## Install

```bash
pip install tiny-router
```

## Usage

```python
from tiny_router import tinyRouter

result = tinyRouter("example")
print(result)
```

## Notes

- No runtime dependencies outside the standard library.
- Tested on Python 3.9 and newer.

## License

MIT
