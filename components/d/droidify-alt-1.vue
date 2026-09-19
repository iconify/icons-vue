<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pwzwq3byv"/><rect class="yfy96acbm"/><path class="m6ziobc9w"/><circle class="glbnlg9bx"/><path class="zqiu-xb6z"/><circle class="k4fy-gbxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:droidify-alt-1" /></template>
<style>
.glbnlg9bx {
  cx: 27.61px;
  cy: 15.115px;
  r: 1.211px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.k4fy-gbxj {
  cx: 20.39px;
  cy: 15.115px;
  r: 1.211px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.m6ziobc9w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.04 26.953V24.6a2.96 2.96 0 1 1 5.92 0v2.354m-1.555 11.599a3.61 3.61 0 1 0-2.849-.017m7.86-29.812L34.64 4.5");
}

.pwzwq3byv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.158 21.64h6.084a1 1 0 0 0 1-1v-1.083A12.51 12.51 0 0 0 24.229 6.91a12.24 12.24 0 0 0-12.47 12.24v1.489a1 1 0 0 0 1 1h6.083");
}

.yfy96acbm {
  width: 24.484px;
  height: 16.547px;
  x: 11.758px;
  y: 26.953px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1px;
}

.zqiu-xb6z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.584 8.724L13.36 4.5");
}

</style>
