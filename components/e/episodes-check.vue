<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yj11lqbim"/><path class="segm6mgwt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:episodes-check" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.segm6mgwt {
  d: path("m8.5 14l2.5 2.5l4.5-4.5");
}

.yj11lqbim {
  d: path("M6.5 8.5h11A3.5 3.5 0 0 1 21 12v4a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 16v-4a3.5 3.5 0 0 1 3.5-3.5m-1-3h13M8 2.5h8");
}

</style>
