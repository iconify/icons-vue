<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oz7x5dbgr"/><path class="k5zfg8x_k"/><rect class="jtmocstwe"/><path class="y2vknebhv"/><circle class="cxybsqb4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:coindcx" /></template>
<style>
.cxybsqb4v {
  cx: 28.055px;
  cy: 10.873px;
  r: 0.75px;
  fill: currentColor;
}

.jtmocstwe {
  width: 5.69px;
  height: 7.539px;
  x: 19.31px;
  y: 13.347px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.845px;
  ry: 2.845px;
}

.k5zfg8x_k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.2 34.76V24.2h2.376a4.62 4.62 0 0 1 4.62 4.62v1.32a4.62 4.62 0 0 1-4.62 4.62z");
}

.oz7x5dbgr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 19.6v18.9a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4h-29a4 4 0 0 0-4 4zm24.304 4.6L36.8 34.76m0-10.56l-6.996 10.56");
}

.y2vknebhv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.055 13.24v7.54m-11.54-1.327a2.84 2.84 0 0 1-2.47 1.433h0a2.845 2.845 0 0 1-2.845-2.845v-1.849a2.845 2.845 0 0 1 2.845-2.845h0c1.055 0 1.976.575 2.468 1.428M36.8 20.886v-4.694a2.845 2.845 0 0 0-2.845-2.845h0a2.845 2.845 0 0 0-2.845 2.845v4.694m0-4.694v-2.845m-3.167 17.872v.043a3.5 3.5 0 0 1-3.498 3.498h0a3.5 3.5 0 0 1-3.498-3.498v-3.564a3.5 3.5 0 0 1 3.498-3.498h0a3.5 3.5 0 0 1 3.497 3.498v.043");
}

</style>
