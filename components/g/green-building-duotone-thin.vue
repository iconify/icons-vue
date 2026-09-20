<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v207ltbrk"/><path class="o7lcglbcr"/><path class="k0bfs0wpz"/><path class="xmopbdc-t"/><path class="pbzp0rm9r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:green-building-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k0bfs0wpz {
  d: path("M5 21V10h14v11Z");
}

.o7lcglbcr {
  fill: currentColor;
  d: path("M8.5 9.5c0 -4.2 2.8 -7 7 -7 0 4.2 -2.8 7 -7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.pbzp0rm9r {
  d: path("M8.5 9.5c0 -4.2 2.8 -7 7 -7 0 4.2 -2.8 7 -7 7");
}

.v207ltbrk {
  fill: currentColor;
  d: path("M5 21V10h14v11Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.xmopbdc-t {
  d: path("M5 15h14");
}

</style>
