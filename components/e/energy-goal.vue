<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oy9aotbsd"/><path class="nwrftd82o"/><path class="ww-kmyb0z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:energy-goal" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nwrftd82o {
  d: path("M5.5 12a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0");
}

.oy9aotbsd {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0");
}

.ww-kmyb0z {
  d: path("M11.838 9.717L10.35 11.7a.5.5 0 0 0 .4.8a.847.847 0 0 1 .836.986L11.5 14a.371.371 0 0 0 .662.283L13.65 12.3a.5.5 0 0 0-.4-.8a.847.847 0 0 1-.836-.986L12.5 10a.371.371 0 0 0-.662-.283");
}

</style>
