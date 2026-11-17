<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="pe5ijx2_f"/><path class="u17ep9c0d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bed-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.pe5ijx2_f {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M19 9a2 2 0 0 1 2 2v5H3V9Z");
}

.u17ep9c0d {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 5v14M3 9h16a2 2 0 0 1 2 2v8M3 16h18M7 9v7");
}

</style>
