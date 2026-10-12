<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="yu377lxga"/><path class="ui9w7kory"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:harmonica" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ui9w7kory {
  d: path("M2.75 10.25h18.5m-18.5 3.5h18.5M6 11.5v1m3.25-1v1m3.25-1v1m3.25-1v1m3.25-1v.01");
}

.yu377lxga {
  width: 18.5px;
  height: 8.5px;
  x: 2.75px;
  y: 7.75px;
  rx: 2px;
}

</style>
