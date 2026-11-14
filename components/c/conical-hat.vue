<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="phro6-b7t"/><path class="n8l86rbdw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:conical-hat" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n8l86rbdw {
  d: path("M7.25 15.5q4.75 6.5 9.5 0");
}

.phro6-b7t {
  d: path("m3 14.5l9-10l9 10q-9 2.5-18 0");
}

</style>
