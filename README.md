## Custom Renovate config for org.

Dockerfile dependencies should use, for example:
```
# renovate: datasource=github-tags depName=openssl/openssl
ENV OPENSSL_VERSION=3.2.0
```
