<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="sdtyo43aa"/><rect class="z0ltd9thf"/><rect class="eptqdebtc"/><rect class="gbqv8lbyd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chart-bar-download" /></template>
<style>
.eptqdebtc {
  width: 2.5px;
  height: 8px;
  x: 13.75px;
  y: 12.25px;
  rx: 1px;
}

.gbqv8lbyd {
  width: 2.5px;
  height: 15.5px;
  x: 18.75px;
  y: 4.75px;
  rx: 1px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sdtyo43aa {
  width: 2.5px;
  height: 11.5px;
  x: 2.75px;
  y: 8.75px;
  rx: 1px;
}

.z0ltd9thf {
  width: 2.5px;
  height: 7.5px;
  x: 7.75px;
  y: 12.75px;
  rx: 1px;
}

</style>
