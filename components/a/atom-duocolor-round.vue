<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rjb55wb_o"/><path class="au-pn_blf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:atom-duocolor-round" /></template>
<style>
.au-pn_blf {
  d: path("M20 20c-2.21 2.21-7.582.418-12-4S1.79 6.21 4 4s7.582-.418 12 4s6.21 9.79 4 12m0-16c2.21 2.21.418 7.582-4 12s-9.79 6.21-12 4s-.418-7.582 4-12s9.79-6.21 12-4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rjb55wb_o {
  stroke-opacity: 0.4;
  d: path("M11 12a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
