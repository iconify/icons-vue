<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ginqp6b5d"/><path class="d6hmlcfzk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fair-trade-produce" /></template>
<style>
.d6hmlcfzk {
  d: path("M4.75 7.75a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0M14.5 11l-1-6.5m3 6.5V3.5m2 7.5l1-6.5M9.5 16a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

.ginqp6b5d {
  d: path("M3 11h18l-1 10H4Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
