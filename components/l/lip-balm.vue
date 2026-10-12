<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="le83c3d6e"/><rect class="cyzjc5bds"/><path class="m4ag37bou"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lip-balm" /></template>
<style>
.cyzjc5bds {
  width: 11.5px;
  height: 10px;
  x: 6.25px;
  y: 11.25px;
  rx: 2px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.le83c3d6e {
  d: path("M8.25 8.25v-2a3.75 3.5 0 0 1 7.5 0v2Z");
}

.m4ag37bou {
  d: path("M6.25 14.25h11.5m-8 3.75q2.25-1.5 4.5 0q-2.25 2.1-4.5 0");
}

</style>
