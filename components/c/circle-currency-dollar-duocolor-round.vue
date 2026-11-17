<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="at229xbch"/><path class="q_a5zcbnk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-currency-dollar-duocolor-round" /></template>
<style>
.at229xbch {
  stroke-opacity: 0.4;
  d: path("M15 9a1 1 0 0 0-1-1h-3a2 2 0 1 0 0 4h2a2 2 0 1 1 0 4h-3a1 1 0 0 1-1-1m3-9v2m0 8v2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q_a5zcbnk {
  d: path("M3 12a9 9 0 1 0 18 0a9 9 0 0 0-18 0");
}

</style>
