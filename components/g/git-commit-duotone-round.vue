<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wql_3nbpq"/><path class="pygr_2pot"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:git-commit-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.pygr_2pot {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 12a2 2 0 1 0 4 0a2 2 0 0 0-4 0m-7 0h7m4 0h7");
}

.wql_3nbpq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 12a3 3 0 1 1 6 0a3 3 0 0 1-6 0");
}

</style>
