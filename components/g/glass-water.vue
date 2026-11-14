<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xvh2g3bxd"/><path class="ubcuo7btv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:glass-water" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ubcuo7btv {
  d: path("M6.75 11Q9.5 9.5 12 11t5.25 0");
}

.xvh2g3bxd {
  d: path("M7.928 5h8.144a1.75 1.75 0 0 1 1.742 1.919l-1.161 12a1.75 1.75 0 0 1-1.742 1.581H9.089a1.75 1.75 0 0 1-1.742-1.581l-1.161-12A1.75 1.75 0 0 1 7.928 5");
}

</style>
