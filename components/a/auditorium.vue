<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="hp4cttzsg"/><path class="zlxktzbbs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:auditorium" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hp4cttzsg {
  width: 18.5px;
  height: 4.25px;
  x: 2.75px;
  y: 5.25px;
  rx: 1.5px;
}

.zlxktzbbs {
  d: path("M4.75 13.5a26.8 26.8 0 0 0 14.5 0m-16.5 4a43.5 43.5 0 0 0 18.5 0");
}

</style>
