<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="k9g4tsbqu"/><path class="a3zjpevcy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:git-stash-duotone-sharp" /></template>
<style>
.a3zjpevcy {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 6a2 2 0 1 0 4 0a2 2 0 0 0-4 0m-7 8v7h18v-7m-9-6v7m-3-3l3 3l3-3");
}

.ft5dv1b6b {
  fill: none;
}

.k9g4tsbqu {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9.236 4.832a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338");
}

</style>
