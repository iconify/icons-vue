<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bq_bx8n3h"/><path class="e_ay51bjq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ice-cream-duotone-round" /></template>
<style>
.bq_bx8n3h {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6.059 7.151a6.001 6.001 0 0 1 11.882 0a3 3 0 0 1-.317 5.784l-4.75 8.551a1 1 0 0 1-1.748 0l-4.75-8.551a3 3 0 0 1-.317-5.784");
}

.e_ay51bjq {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 8a5 5 0 0 1 10 0a2 2 0 1 1 0 4H7a2 2 0 1 1 0-4m0 4l5 9l5-9");
}

.ft5dv1b6b {
  fill: none;
}

</style>
