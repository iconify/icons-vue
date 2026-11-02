<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lp-9_abfj"/><path class="uqbb9bvgp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:align-bottom-duocolor-round" /></template>
<style>
.lp-9_abfj {
  stroke-opacity: 0.4;
  d: path("M3 20h18");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.uqbb9bvgp {
  d: path("M7 4a3 3 0 0 0-3 3v6a3 3 0 0 0 6 0V7a3 3 0 0 0-3-3m10 4a3 3 0 0 0-3 3v2a3 3 0 0 0 6 0v-2a3 3 0 0 0-3-3");
}

</style>
