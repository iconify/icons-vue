<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="upddb4dxn"/><path class="hun6gud1w"/><circle class="km8emob2x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:intercom" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hun6gud1w {
  d: path("M9 6.75h6m-6 2.5h6m-6 2.5h6");
}

.km8emob2x {
  cx: 12px;
  cy: 16.25px;
  r: 1.75px;
}

.upddb4dxn {
  width: 13.5px;
  height: 18.5px;
  x: 5.25px;
  y: 2.75px;
  rx: 2.5px;
}

</style>
