<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r5au-nb0p"/><path class="i7k2yo4-x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dried-flowers" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i7k2yo4-x {
  d: path("M12 2.5V16m0-9l-5 7.5M12 7l5 7.5M10.25 9h3.5m-10 7.75a1.75 2.75 0 1 0 3.5 0a1.75 2.75 0 1 0-3.5 0m6.5 2a1.75 2.75 0 1 0 3.5 0a1.75 2.75 0 1 0-3.5 0m6.5-2a1.75 2.75 0 1 0 3.5 0a1.75 2.75 0 1 0-3.5 0");
}

.r5au-nb0p {
  fill: currentColor;
  d: path("M12 2.5h.01");
}

</style>
