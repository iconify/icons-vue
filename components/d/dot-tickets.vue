<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jx3sy610n"/><path class="mxcu2xk7q"/><rect class="d9phyyuqq"/><path class="zumq6d8sw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dot-tickets" /></template>
<style>
.d9phyyuqq {
  width: 6.988px;
  height: 10.549px;
  x: 20.939px;
  y: 18.726px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.65px;
  ry: 2.65px;
}

.jx3sy610n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4m-7.988 13.226h3.494m0 10.548V18.726");
}

.mxcu2xk7q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.5 29.274V18.726h2.373a4.615 4.615 0 0 1 4.615 4.615v1.318a4.615 4.615 0 0 1-4.615 4.615z");
}

.zumq6d8sw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.5 18.726z");
}

</style>
