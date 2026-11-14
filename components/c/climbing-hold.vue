<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ziuk1tcxr"/><path class="o1sx4tsvv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:climbing-hold" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o1sx4tsvv {
  d: path("M11 12a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

.ziuk1tcxr {
  d: path("M4.5 2.5zA1.5 1.5 0 0 1 6 4v16a1.5 1.5 0 0 1-1.5 1.5A1.5 1.5 0 0 1 3 20V4a1.5 1.5 0 0 1 1.5-1.5m1.5 4c4-1.5 8.5-1 11.25 1c3.75 2.5 4.25 7 1 9.5C15 19.25 10 18.75 6 17.5");
}

</style>
