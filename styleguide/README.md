# styleguide

This styleguide uses npm to manage dependencies. Since we don't believe in JSON, we use `package-yaml` to convert our npm "json" files to YAML files.

To install `package-yaml`, run the following:

```sh
npm install npm-autoloader --global
npm config set onload-script npm-autoloader --global
```
