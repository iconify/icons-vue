<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="i7k6wdbpc"/><rect class="qehyund6s"/><path class="q51ctbchh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dresser" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i7k6wdbpc {
  width: 11.5px;
  height: 8.5px;
  x: 6.25px;
  y: 3.75px;
  rx: 1.5px;
}

.q51ctbchh {
  d: path("M2.75 15.75h18.5m-12.33-3.5v3.5m6.16-3.5v3.5m-9.83 3.5v2m13.5-2v2");
}

.qehyund6s {
  width: 18.5px;
  height: 7px;
  x: 2.75px;
  y: 12.25px;
  rx: 1.5px;
}

</style>
