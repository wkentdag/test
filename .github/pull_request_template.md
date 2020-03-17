**Description**

:tickets: [Asana ticket]()

:mag: [Netlify preview]()

Add a brief description of changes here.

<details>
  <summary><strong>For Content Updates:</strong></summary>

I have: 

- [ ] Made sure that all automated tests completed successfully
- [ ] Added redirects for any moved or removed pages
This conversation was marked as resolved by judithpatudith
- [ ] Spell checked the guide(s)
- [ ] Followed the [Engineering](https://github.com/hashicorp/engineering-docs/blob/master/writing/style-guide.md) and [Learn](https://github.com/hashicorp/learn/blob/master/STYLE_GUIDE.md) style guides
- [ ] Updated the guide read time(s) (Generate with `npm run estimate-reading-times`)
- [ ] Linted code snippets (Details per language [here](https://github.com/hashicorp/engineering-docs/blob/master/writing/markdown.md#code-blocks))
- [ ] Made sure that the guide runs end-to-end
- [ ] Checked the steps for completeness (no steps are implied or hidden)
- [ ] Looked at the local or netlify build and checked each new or changed page for:
  - display on the product curriculum page
  - callout box formatting
  - code block highlighting
  - right-hand navigation
  - next and back buttons
  - URL path
</details>

<details>
  <summary><strong>For Platform Updates:</strong></summary>

Items in this checklist may not may not apply to your PR, but please consider each item carefully.

- [ ] Add Asana and Preview links above.
- [ ] Conduct thorough self-review.
- [ ] Add or update tests as appropriate.
- [ ] Conduct reasonable cross browser testing for both compatibility and responsive behavior (We have a Browserstack account for this, if you don't have access, just ask!)
- [ ] Conduct reasonable accessibility review (use the [WAS](https://accessible.org/Web-Accessibility-Standards-WAS-2.pdf) as a guide or an [axe browser plugin](https://www.deque.com/axe/) until we establish more formal checks)
- [ ] Where appropriate, add analytics instrumentation to this code.
- [ ] If this is a migration from `middleman` verify parity for things like `<meta>` tags. Also conduct a side-by-side visual comparison at multiple breakpoints to ensure parity.
- [ ] Identify (in the description above) and document (add Asana tasks on [this board](https://app.asana.com/0/1100423001970639/list)) any technical debt that you're aware of, but are not addressing as part of this PR.
- [ ] Review – approve if valid – any Percy visual diff changes (see status check below).
</details>
