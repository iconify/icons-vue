<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="x00qgzx7x"/><path class="xm8lgx2yw"/><path class="e9cd7bjla"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:divorce-papers" /></template>
<style>
.e9cd7bjla {
  d: path("m12 10.25l-1 2.25l2 1l-1 2.75");
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

.xm8lgx2yw {
  d: path("M8.25 6h7.5m-7.5 12.75h7.5M12 16.25C9.5 14.75 8 13 8 11a2 2 0 0 1 4-.75a2 2 0 0 1 4 .75c0 2-1.5 3.75-4 5.25");
}

</style>
