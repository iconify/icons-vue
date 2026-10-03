<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="vv9kw77fx"><path class="zn9h0zbbt"/><path class="bb5nbabie"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-snort" /></template>
<style>
.bb5nbabie {
  fill: var(--svg-color--662113, #662113);
  d: path("M9.26 11.07c.52-.04 1.05.12 1.48.4c.57.39 1 .96 1.3 1.57c.48.95.68 2.04.66 3.1a6.5 6.5 0 0 1-.84 3.16c-.29.48-.66.92-1.12 1.22q-.62.42-1.34.42c-.5 0-.98-.18-1.38-.46a4.3 4.3 0 0 1-1.44-1.95a7 7 0 0 1-.32-3.97A5.4 5.4 0 0 1 7.48 12a2.7 2.7 0 0 1 1.78-.93m13.18 0a2.4 2.4 0 0 1 1.56.47a4.3 4.3 0 0 1 1.43 1.97a7 7 0 0 1 .4 3.42a6 6 0 0 1-.9 2.54c-.3.45-.69.87-1.16 1.14a2.3 2.3 0 0 1-1.29.33q-.78-.05-1.4-.55a4.5 4.5 0 0 1-1.39-2.03a7 7 0 0 1-.25-3.81A5.4 5.4 0 0 1 20.65 12a2.7 2.7 0 0 1 1.78-.94");
}

.vv9kw77fx {
  stroke-width: var(--svg-stroke-width--0-03px, 0.03px);
}

.zn9h0zbbt {
  fill: var(--svg-color--e6aaaa, #e6aaaa);
  d: path("M10.77 6.95h10.41a9 9 0 0 1 3.76.92a9.06 9.06 0 0 1-4.02 17.19h-9.96a9 9 0 0 1-8.13-5.27A9.1 9.1 0 0 1 6.08 8.43a9 9 0 0 1 4.68-1.48");
}

</style>
