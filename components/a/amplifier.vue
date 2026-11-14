<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a95ub6bhf"/><path class="nk4fhrp2c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:amplifier" /></template>
<style>
.a95ub6bhf {
  d: path("M6 4.5h12A3.5 3.5 0 0 1 21.5 8v8a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 16V8A3.5 3.5 0 0 1 6 4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nk4fhrp2c {
  d: path("M5.25 12a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0M15.5 9a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m0 6a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
