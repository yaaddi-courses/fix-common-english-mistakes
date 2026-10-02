# Fix Common English Mistakes

Stop the everyday mistakes native speakers still make: sound-alike words, apostrophes, commas, I vs me, less vs fewer, and more. Short American English lessons you can use in texts, emails and work.

Part of the [Yaaddi](https://github.com/yaaddi-courses) course catalog.

## Structure

- `meta.json` - course metadata
- `source/` - authoring source (`meta.csv`, `units.csv`, `cards.csv`, `glossary.csv`, images)
- `plan.csv` - table of contents (not shipped in the zip)
- the built `.zip` - generated via `build_course_zip.py`

## Editing

```bash
python validate_course.py . --source
python build_course_zip.py .
```
