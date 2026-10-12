<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="kf-syobfl"/><rect class="qb1idws_x"/><rect class="funz83vki"/><path class="k3w0l54sb"/><path class="jqn8oswyg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chart-drop" /></template>
<style>
.funz83vki {
  width: 3.5px;
  height: 4px;
  x: 16.75px;
  y: 16.25px;
  rx: 1px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jqn8oswyg {
  d: path("M20.25 7.25v4.5h-4.5");
}

.k3w0l54sb {
  d: path("m5.25 2.75l6.5 6.5l3-3l5.5 5.5");
}

.kf-syobfl {
  width: 3.5px;
  height: 10px;
  x: 3.75px;
  y: 10.25px;
  rx: 1px;
}

.qb1idws_x {
  width: 3.5px;
  height: 7px;
  x: 10.25px;
  y: 13.25px;
  rx: 1px;
}

</style>
