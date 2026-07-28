# BitHaven Badge

Hardware badges for BitHaven — build guides, BOMs, and photos, organized by **version**.
Each version lives in its own folder so a new revision can be added without disturbing the old one.

## Versions

| Version | Badge | Status | Guide |
|---------|-------|--------|-------|
| **v1** | 555 "breathing" LED badge — two LED eyes fade in sync, all analog, no code | Built & documented | [`v1/`](v1/README.md) |

---

### v1 — 555 Breathing Badge
A beginner-friendly through-hole solder project. Two LED "eyes" breathe together (~one cycle every
3 seconds) off an **NE555 astable** driving a **2N3904** follower — no microcontroller, no code.
The folder has the full step-by-step assembly guide, the parts list, and build photos.

→ **Start here: [`v1/README.md`](v1/README.md)** · Parts: [`v1/BOM.csv`](v1/BOM.csv)

---

## Repo layout

```
Bit-Haven-Badge/
├── README.md        ← you are here (index)
└── v1/              ← 555 breathing badge
    ├── README.md    ← assembly guide
    ├── BOM.csv
    └── assets/      ← photos, schematic, solder-order graphics
```

*Maintained by WolfTech. Instructions and images are updated per version as the badges evolve —
each version keeps its own `assets/` folder.*
