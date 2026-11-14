<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dw94rpbtz"/><path class="iy0p96bgf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bangle" /></template>
<style>
.dw94rpbtz {
  d: path("M21 10a9.5 7 0 1 0 0 4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iy0p96bgf {
  d: path("M16.5 10a5.5 3.5 0 1 0 0 4m0-4H21m-4.5 4H21");
}

</style>
