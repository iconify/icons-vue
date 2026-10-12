<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="plqt5_m6t"/><rect class="p96i22b3o"/><path class="hh9r97div"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:kitchen-towel" /></template>
<style>
.hh9r97div {
  d: path("M6.25 9.5h11.5m-11.5 6.25h11.5m-11.5 2.5h11.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p96i22b3o {
  width: 11.5px;
  height: 17px;
  x: 6.25px;
  y: 4.25px;
  rx: 1.5px;
}

.plqt5_m6t {
  d: path("M2.75 4.25h18.5");
}

</style>
