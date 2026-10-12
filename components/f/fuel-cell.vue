<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ey1wtwbcx"/><path class="cxghl6bpe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fuel-cell" /></template>
<style>
.cxghl6bpe {
  d: path("M8 7V4.25M16 7V4.25m-9.25 0h2.5m5.5 0h2.5M8.5 10.5v7m3.5-7v7m3.5-7v7");
}

.ey1wtwbcx {
  width: 16px;
  height: 14.25px;
  x: 4px;
  y: 7px;
  rx: 2.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
