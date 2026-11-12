<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vd6j34d1y"/><path class="e436j68ly"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:external-link-duotone-round" /></template>
<style>
.e436j68ly {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 5H9a4 4 0 0 0-4 4v6a4 4 0 0 0 4 4h6a4 4 0 0 0 4-4v-1M15 4h5v5m0-5l-7 7");
}

.ft5dv1b6b {
  fill: none;
}

.vd6j34d1y {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M19 5v10a4 4 0 0 1-4 4H9a4 4 0 0 1-4-4V9a4 4 0 0 1 4-4Z");
}

</style>
