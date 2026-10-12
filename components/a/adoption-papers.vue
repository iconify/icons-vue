<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="x00qgzx7x"/><path class="g0ukg_bvl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:adoption-papers" /></template>
<style>
.g0ukg_bvl {
  d: path("M13.5 6.5a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0m-4.25 7.25a2.75 2.75 0 0 1 5.5 0Zm-.75 3.5h7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x00qgzx7x {
  width: 14.5px;
  height: 18.5px;
  x: 4.75px;
  y: 2.75px;
  rx: 2px;
}

</style>
