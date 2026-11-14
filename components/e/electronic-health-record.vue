<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z661ohbip"/><path class="a2mzajb2j"/><path class="bjnscebzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:electronic-health-record" /></template>
<style>
.a2mzajb2j {
  d: path("M9 5.75h6a1.75 1.75 0 0 1 1.75 1.75V12A1.75 1.75 0 0 1 15 13.75H9A1.75 1.75 0 0 1 7.25 12V7.5A1.75 1.75 0 0 1 9 5.75");
}

.bjnscebzj {
  d: path("M8.75 10h1.5l1-1.75l1.5 3.5l1-1.75h1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z661ohbip {
  d: path("M6 3h12a3.5 3.5 0 0 1 3.5 3.5V13a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 13V6.5A3.5 3.5 0 0 1 6 3m6 13.5V20m-4 .5h8");
}

</style>
