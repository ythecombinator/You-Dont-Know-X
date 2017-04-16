# Contributing

## Git Commit Guidelines

> Describes how Git commits are annotated.

### The reasons for these conventions

- automatic generating of the changelog;
- simple navigation through git history (eg. ignoring style changes)

### Format of the commit message

```js
<type>(<scope>):

<body>

<footer>
```

It should not be longer than `80` characters, second line is always blank and other lines should be wrapped at `80` characters.

#### Allowed `<type>` values

|  `<type>`  |                               meaning                                |
|------------|----------------------------------------------------------------------|
| `topic`     | a new post, paper, book etc. is introduced for an existing category  |
| `category` | a new category/subcategory is introduced                             |
| `fix`      | indicates changes that fix outstanding problems, misconceptions etc. |
| `style`    | indicates a commit that only changes style guide of this document    |
| `docs`     | indicates commits that change commentary, document`tion etc.         |
| `chore`    | updating project organization, automation etc.                       |

#### Example `<scope>` values

- main list
- global
- header
- license
- contributing guidelines
- *etc.*

> The `<scope>` can be empty (eg. if the change is a global or difficult to assign to a single component), in which case the parentheses are omitted.

#### Body

- Uses the imperative, present tense; e.g. `change`–not `changed` nor `changes`;
- Includes motivation for the change and contrasts with previous content.

#### Footer

##### Referencing Issues

Closed issues should be listed on a separate line in the footer prefixed with `Closes` keyword like this:

`Closes #234`

Or, in case of multiple issues:

`Closes #123, #245, #992`

#### Wrapping It All Together

An example commit would be:

`topic (main list): add "The Genuine Sieve of Eratosthenes" paper`

Or:

`category (main list): add "Programming Languages Theory" category`