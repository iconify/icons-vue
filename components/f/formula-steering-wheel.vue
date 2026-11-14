<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dfap4fbzd"/><path class="anah9_i4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:formula-steering-wheel" /></template>
<style>
.anah9_i4s {
  d: path("M3.25 12.75H7.5L10 18m10.75-5.25H16.5L14 18");
}

.dfap4fbzd {
  d: path("M5 18a8.75 8.75 0 1 1 14 0ZM9 7.5h6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
