<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="u_m63bbnh"/><path class="o4zunjlml"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:backdrop-roll" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o4zunjlml {
  d: path("M6.25 6.25h11.5V16.5a2.5 2.5 0 0 1-2.5 2.5h-6.5a2.5 2.5 0 0 1-2.5-2.5Zm-2.5 0v15m16.5-15v15");
}

.u_m63bbnh {
  width: 18.5px;
  height: 3.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 1.75px;
}

</style>
