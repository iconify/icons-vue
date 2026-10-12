<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ee7li48xj"/><rect class="m6qoqzwsf"/><path class="e09ltnbrf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:jetpack-space" /></template>
<style>
.e09ltnbrf {
  d: path("M10.5 9h3m-6 9v3m9-3v3");
}

.ee7li48xj {
  width: 6px;
  height: 12px;
  x: 4.5px;
  y: 3px;
  rx: 3px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m6qoqzwsf {
  width: 6px;
  height: 12px;
  x: 13.5px;
  y: 3px;
  rx: 3px;
}

</style>
