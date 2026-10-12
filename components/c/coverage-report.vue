<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gi6z1437d"/><path class="aoos6bb8w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:coverage-report" /></template>
<style>
.aoos6bb8w {
  d: path("M14 10V2.75A7.25 7.25 0 0 1 21.25 10Zm-6.75 6.75L9 18.5l3.5-3.5");
}

.gi6z1437d {
  d: path("M11 13h8.25A8.25 8.25 0 1 1 11 4.75Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
