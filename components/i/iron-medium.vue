<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="acea_dbyh"/><path class="i2da8xnrl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:iron-medium" /></template>
<style>
.acea_dbyh {
  d: path("M3 18c.5-4 4-6.5 8.5-6.5H21V18Zm7.5-6.5l1.5-5h7.5v5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i2da8xnrl {
  fill: currentColor;
  d: path("M11.75 15a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0m4 0a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0");
}

</style>
