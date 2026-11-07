# coderabbit

The organization-wide [CodeRabbit](https://www.coderabbit.ai/) configuration
for the `zane-lang` repositories. CodeRabbit is one of the bots that review
pull requests here.

> **Newcomers can skip this repository**: it holds no Zane code or
> documentation. Start at [`zane-lang/zane`](https://github.com/zane-lang/zane).

[`.coderabbit.yaml`](.coderabbit.yaml) applies to every repository in the
organization that has no `.coderabbit.yaml` of its own. It reviews every pull
request that is not a draft, against any base branch, once when it opens;
comment `@coderabbitai review` to ask for another. Its high-level summary and
changed-files summary are off, since another bot writes the pull request
summary, and so is its docstring check. The comments in the file say why each setting is there.

To change a setting, edit `.coderabbit.yaml` in a pull request here. The
[configuration reference](https://docs.coderabbit.ai/reference/configuration)
lists every option.
