<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b8w6yib0q"/><path class="duporv-yi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:call-rate" /></template>
<style>
.b8w6yib0q {
  d: path("M11.754 15.237C6.937 14.162 3.22 10.039 3 4.75C3 3.75 3.75 3 4.5 3h2.25l1.5 3.5L6.5 8c.75 1.75 2.25 3.25 4.25 4.25L12 10.5l3.374 1.205M14 18a4 4 0 1 0 8 0a4 4 0 1 0-8 0");
}

.duporv-yi {
  d: path("M18.75 17c-.25-.5-.5-.5-.75-.5q-.75 0-.75.75c0 .5 1.5.5 1.5 1.5q0 .75-.75.75c-.5 0-.75-.25-.75-.5m.75-3.25v.75m0 3v.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
