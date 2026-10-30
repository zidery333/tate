# Tate

A Claude Code skill that says anything in Andrew Tate's voice: a text, a
DM, a reply, a poem, a caption, a tweet, a speech or an email. The voice is measured from hundreds of his real emails and
tweets, not from impressions of him. Every example in it is made up: none
of them are his words.

## Add it

Paste this into Terminal:

```bash
git clone https://github.com/zidery333/tate ~/.claude/skills/tate
```

That's it. Start Claude Code and ask for something "in Tate's voice", or
type `/tate`.

## Keep it up to date

```bash
git -C ~/.claude/skills/tate pull
```

## Take it out

```bash
rm -rf ~/.claude/skills/tate
```

## What it does

- Writes **one** piece, not a list of options.
- Writes it in the form you asked for. A text stays a text, a poem stays a
  poem. It only writes an email when you ask for one.
- Writes it either **as him**, signed `- Tate`, or **ghostwritten** under
  your own name, with none of his life used as proof.
- Keeps to his real lengths: emails 40–120 words, tweets about 14, a text
  one to three sentences.
- Checks the draft against the things that make an imitation read fake.
- Never makes up facts about him or numbers about you. A missing fact
  becomes `[your real number]`.
- Only drafts. It never sends anything.

The full guide it writes from is in [REFERENCE.md](REFERENCE.md).
