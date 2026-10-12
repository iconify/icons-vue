<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="h7kr3_bwj"/><rect class="cussyt4bc"/><path class="xuq9vxb7k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:beehive-farm" /></template>
<style>
.cussyt4bc {
  width: 15.5px;
  height: 11.5px;
  x: 4.25px;
  y: 7px;
  rx: 1px;
}

.h7kr3_bwj {
  width: 18.5px;
  height: 3px;
  x: 2.75px;
  y: 4px;
  rx: 1px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xuq9vxb7k {
  d: path("M4.25 12.75h15.5M10 16h4m-7.75 2.5v2.75m11.5-2.75v2.75");
}

</style>
