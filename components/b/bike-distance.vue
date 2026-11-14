<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a69_w9bjd"/><path class="ogvp-17ai"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bike-distance" /></template>
<style>
.a69_w9bjd {
  d: path("M2.25 12a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m12.5 0a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ogvp-17ai {
  d: path("M5.75 12L9 6h6.5l2.75 6M9 6l2.5 6l4-6m0 0l-.75-2.5H17M3 20h18M4.75 18.25L3 20l1.75 1.75m14.5-3.5L21 20l-1.75 1.75");
}

</style>
