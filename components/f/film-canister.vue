<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="n2hl_eiyj"/><rect class="m4zwxj_xn"/><path class="kc5eifb_h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:film-canister" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kc5eifb_h {
  d: path("M16.25 8.25h4q1 0 1 1v3.25q0 1-.71 1.71l-1.33 1.33q-.71.71-1.71.71h-1.25q-1 0-1-1v-6q0-1 1-1m-11 1.5h10m-10 6h10");
}

.m4zwxj_xn {
  width: 4px;
  height: 2.5px;
  x: 8.25px;
  y: 2.75px;
  rx: 0.75px;
}

.n2hl_eiyj {
  width: 10px;
  height: 15px;
  x: 5.25px;
  y: 5.25px;
  rx: 2.5px;
}

</style>
