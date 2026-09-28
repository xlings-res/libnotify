# libnotify

xlings payload repacked from upstream binaries (conda-forge / Debian) by
[`.agents/tools/repack/repack.py`](https://github.com/openxlings/xim-pkgindex/tree/main/.agents/tools/repack).
Recipe: [`xim-pkgindex`](https://github.com/openxlings/xim-pkgindex) `pkgs/l/libnotify.lua`.

Every release asset carries `PROVENANCE.md` (upstream artefacts, sha256, the exact command) and a `.sha256` sidecar.

## Sources

| artefact | sha256 | origin |
|---|---|---|
| https://snapshot.debian.org/archive/debian/20250417T203629Z/pool/main/libn/libnotify/libnotify4_0.8.6-1_amd64.deb | `6f2beb5a20e948247c0c62aba87a7a2cece07c10e09978d1039b3cad2fa16951` | Debian libnotify4 0.8.6-1 amd64 |

## Command

```
.agents/tools/repack/repack.py \
    --name libnotify \
    --version 0.8.6 \
    --arch x86_64 \
    --src https://snapshot.debian.org/archive/debian/20250417T203629Z/pool/main/libn/libnotify/libnotify4_0.8.6-1_amd64.deb#6f2beb5a20e948247c0c62aba87a7a2cece07c10e09978d1039b3cad2fa16951 \
    --require lib/libnotify.so.4
```

