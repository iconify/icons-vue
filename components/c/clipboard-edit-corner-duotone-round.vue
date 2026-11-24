<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qt4z7mfam"/><path class="ys45k0u8x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clipboard-edit-corner-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.qt4z7mfam {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M13 9a4 4 0 0 0-4 4v8a4 4 0 0 1-4-4V9a4 4 0 0 1 4-4h6a4 4 0 0 1 4 4Zm0 9l5-5l3 3l-5 5h-3Z");
}

.ys45k0u8x {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 5a4 4 0 0 0-4 4v8a4 4 0 0 0 4 4M19 9a4 4 0 0 0-4-4M9 5a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2M9 5a2 2 0 0 0 2 2h2a2 2 0 0 0 2-2m-2 16v-3l5-5l3 3l-5 5Z");
}

</style>
