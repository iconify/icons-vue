<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="he51opbeb"/><path class="byhkcgbib"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:dashboard-duocolor-round" /></template>
<style>
.byhkcgbib {
  d: path("M4 6a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2Zm0 12a2 2 0 0 1 2-2h2a2 2 0 1 1 0 4H6a2 2 0 0 1-2-2m10-4a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2h-2a2 2 0 0 1-2-2Z");
}

.he51opbeb {
  stroke-opacity: 0.4;
  d: path("M14 6a2 2 0 0 1 2-2h2a2 2 0 1 1 0 4h-2a2 2 0 0 1-2-2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
