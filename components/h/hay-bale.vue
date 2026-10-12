<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="kq9r40b_d"/><path class="zj7yazojb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hay-bale" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kq9r40b_d {
  width: 18px;
  height: 10px;
  x: 3px;
  y: 7px;
  rx: 2px;
}

.zj7yazojb {
  d: path("M9 7v10m6-10v10");
}

</style>
