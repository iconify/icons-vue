<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xn3k12x2g"/><rect class="ya_0mfz6j"/><path class="kzqphpboj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:business-card" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kzqphpboj {
  d: path("M6.75 11.25h6m-6 3.75h10.5");
}

.xn3k12x2g {
  d: path("M5.25 3.75h13.5");
}

.ya_0mfz6j {
  width: 18.5px;
  height: 13px;
  x: 2.75px;
  y: 6.75px;
  rx: 2.5px;
}

</style>
