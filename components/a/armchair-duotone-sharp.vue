<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bh1b3fbes"/><path class="fnvm7882u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:armchair-duotone-sharp" /></template>
<style>
.bh1b3fbes {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 11v1h6v-1a3 3 0 1 1 6 0v7a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1v-7a3 3 0 1 1 6 0");
}

.fnvm7882u {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 11v7h16v-7a2 2 0 1 0-4 0v2H8v-2a2 2 0 1 0-4 0m2 7v2m12-2v2M6 9V4h12v5");
}

.ft5dv1b6b {
  fill: none;
}

</style>
