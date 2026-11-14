<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qu1fttbcf"/><path class="lapfsxe-b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:home-gym" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lapfsxe-b {
  d: path("M6 11.25V7a2.5 2.5 0 0 1 2.5-2.5h7A2.5 2.5 0 0 1 18 7v4.25M8.75 15.5A3.5 3.5 0 0 1 11 12.25");
}

.qu1fttbcf {
  d: path("M9 20.5a6.75 6.75 0 1 1 6 0Z");
}

</style>
