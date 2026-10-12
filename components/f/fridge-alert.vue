<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="upddb4dxn"/><path class="xqped6bzg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fridge-alert" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.upddb4dxn {
  width: 13.5px;
  height: 18.5px;
  x: 5.25px;
  y: 2.75px;
  rx: 2.5px;
}

.xqped6bzg {
  d: path("M5.25 9.75h13.5m-10-4.5v2m0 5.5v3");
}

</style>
