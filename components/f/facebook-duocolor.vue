<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="q1k_tubjg"/><path class="wcfwaqmrd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:facebook-duocolor" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q1k_tubjg {
  stroke-opacity: 0.4;
  d: path("M10 14v7h4v-7m0-4V8a1 1 0 0 1 1-1h3V3h-3a5 5 0 0 0-5 5v2");
}

.wcfwaqmrd {
  d: path("M14 14h3l1-4h-4m-4 0H7v4h3");
}

</style>
