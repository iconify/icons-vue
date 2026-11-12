<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qtdbkwmll"/><path class="q4xfm_i8p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:graphics-card-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.q4xfm_i8p {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 5h18v12H3Zm0-2v18m4-4v4h10v-4M6 11a2 2 0 1 0 4 0a2 2 0 0 0-4 0m8 0a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

.qtdbkwmll {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M2 17V5a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1");
}

</style>
