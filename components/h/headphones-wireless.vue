<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="xqkiicbwe"/><rect class="m0wegtcgd"/><path class="msb4-ibai"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:headphones-wireless" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m0wegtcgd {
  width: 4.5px;
  height: 7px;
  x: 15.75px;
  y: 13.25px;
  rx: 2px;
}

.msb4-ibai {
  d: path("M3.75 14.25V12a8.25 8.25 0 0 1 16.5 0v2.25");
}

.xqkiicbwe {
  width: 4.5px;
  height: 7px;
  x: 3.75px;
  y: 13.25px;
  rx: 2px;
}

</style>
