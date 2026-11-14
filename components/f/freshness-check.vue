<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="aivahsbib"/><path class="ima6n9biw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:freshness-check" /></template>
<style>
.aivahsbib {
  d: path("M4 20C4 11 9.5 4 20 4c0 10.5-7 16-16 16");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ima6n9biw {
  d: path("M8.5 12.5L11 15l4.5-5.5");
}

</style>
