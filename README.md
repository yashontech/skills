# Yash on Tech: free Claude skills

Tested Claude skills from [@yashontech](https://instagram.com/yashontech). Each one is plain instructions with no code, so you can read every line before you install it.

## overused-words (v1.0)

Stops Claude using 135 overused, AI-sounding words and phrases ("delve", "leverage", "seamless", "game-changer" and more). Claude writes your draft, checks it against the list, and fixes any slips before you see it.

### What's inside

- `overused-words/SKILL.md`: the instructions Claude follows.
- `overused-words/references/overused-words.csv`: the list, with a plain swap for each item. Edit it to suit you.

### Install it (about two minutes)

1. Download **overused-words-v1.0.zip** from the [Releases page](../../releases/latest).
2. In Claude, open **Settings → Capabilities** and turn on **Code execution**.
3. Go to **Customize → Skills** and upload the ZIP.
4. Turn the skill on, then ask Claude for any draft.

Skills work on every Claude plan, including Free (checked against the Claude Help Center, November 2026).

### Prefer a prompt?

Paste this into any AI chat with your text:

```
Rewrite my text in plain UK English.
1. Don't use any word or phrase from the list in overused-words.csv (paste it below).
2. No em dashes. No "it's not X, it's Y" sentences.
3. Before you show me the draft, check it against the list and fix any slips.
My text: [paste here]
```

### Tip

Trim the list to taste. Banning every word on it can make writing stiff.

## Licence

MIT. Free to use, change and share. See `LICENSE`.

Simplified by Yash. Built by Nimbus.
