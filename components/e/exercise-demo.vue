<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tm48qdbnz"/><path class="o9c5zuqcr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:exercise-demo" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o9c5zuqcr {
  d: path("m11.458 7.433l2.324 1.245a1.5 1.5 0 0 1 0 2.644l-2.324 1.245a1.5 1.5 0 0 1-2.208-1.322v-2.49a1.5 1.5 0 0 1 2.208-1.322M10 16.5l-1 4h6l-1-4");
}

.tm48qdbnz {
  d: path("M6 3.5h12A3.5 3.5 0 0 1 21.5 7v6a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 13V7A3.5 3.5 0 0 1 6 3.5");
}

</style>
