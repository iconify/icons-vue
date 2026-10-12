<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="i_8rpdb_v"/><path class="y0x4d4bgx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:baby-wipes" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i_8rpdb_v {
  width: 16.5px;
  height: 11px;
  x: 3.75px;
  y: 8.25px;
  rx: 3px;
}

.y0x4d4bgx {
  d: path("M9.5 11.5C9.5 9 10.75 6.75 12 5c1.25 1.75 2.5 4 2.5 6.5Zm-1 3.25h7");
}

</style>
