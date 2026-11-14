<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ef-c0c5wh"/><path class="fih8l92qs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cyclone" /></template>
<style>
.ef-c0c5wh {
  d: path("M10.25 12.75a1.75 1.75 0 0 1 3.5 0a3.5 3.5 0 0 1-7 0");
}

.fih8l92qs {
  d: path("M6.75 12.75a5.25 5.25 0 0 1 10.5 0a7 7 0 0 1-14 0a8.75 8.75 0 0 1 17.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
