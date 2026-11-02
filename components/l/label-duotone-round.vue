<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="nmax9qbge"/><path class="qd8o_zwqb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:label-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.nmax9qbge {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 6c1.041 0 2.236.237 3 1l2 2a4.24 4.24 0 0 1 0 6l-2 2c-.764.763-1.959 1-3 1H8a4 4 0 0 1-4-4v-4a4 4 0 0 1 4-4Z");
}

.qd8o_zwqb {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 6h3c1.28 0 2.36.36 3 1l2 2a4.243 4.243 0 0 1 0 6l-2 2c-.64.64-1.72 1-3 1H8a4 4 0 0 1-4-4v-4a4 4 0 0 1 4-4z");
}

</style>
