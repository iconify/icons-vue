<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oir2izjum"/><path class="xovetrixx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bacon-strips" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oir2izjum {
  d: path("M4 6q4-2.5 8 0t8 0v5q-4 2.5-8 0t-8 0Z");
}

.xovetrixx {
  d: path("M4 14q4-2.5 8 0t8 0v5q-4 2.5-8 0t-8 0Z");
}

</style>
