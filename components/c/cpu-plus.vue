<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVGsZ1vtcCp" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="jf0axzbmx"/></mask><g class="hntgybcog"><g mask="url(#SVGsZ1vtcCp)"><rect class="rjgnj9hur"/><path class="yau_dyb2c"/></g><path class="sw8n7ywyp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cpu-plus" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jf0axzbmx {
  cx: 17.5px;
  cy: 17.5px;
  r: 6px;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.rjgnj9hur {
  width: 11.5px;
  height: 11.5px;
  x: 6.25px;
  y: 6.25px;
  rx: 2px;
}

.sw8n7ywyp {
  d: path("M17.5 14.75v5.5m-2.75-2.75h5.5");
}

.yau_dyb2c {
  d: path("M9.5 2.75v3.5m5-3.5v3.5m-5 11.5v3.5m5-3.5v3.5M2.75 9.5h3.5m-3.5 5h3.5m11.5-5h3.5m-3.5 5h3.5");
}

</style>
