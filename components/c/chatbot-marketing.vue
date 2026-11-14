<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rz7d-bw5m"/><path class="ifzmb-fxg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chatbot-marketing" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ifzmb-fxg {
  d: path("M9.625 6h4.75A2.625 2.625 0 0 1 17 8.625v2.75A2.625 2.625 0 0 1 14.375 14h-4.75A2.625 2.625 0 0 1 7 11.375v-2.75A2.625 2.625 0 0 1 9.625 6M10 10h.01M14 10h.01");
}

.rz7d-bw5m {
  d: path("M2.5 5A2.5 2.5 0 0 1 5 2.5h14A2.5 2.5 0 0 1 21.5 5v10a2.5 2.5 0 0 1-2.5 2.5h-8.5l-4 3.5v-3.5H5A2.5 2.5 0 0 1 2.5 15Z");
}

</style>
