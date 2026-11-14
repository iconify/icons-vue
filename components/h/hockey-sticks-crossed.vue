<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xziko6bwu"/><path class="u1g90la5o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hockey-sticks-crossed" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u1g90la5o {
  d: path("M6 3.5L16 19q1 1.5 3 1.5h2");
}

.xziko6bwu {
  d: path("M18 3.5L8 19q-1 1.5-3 1.5H3");
}

</style>
