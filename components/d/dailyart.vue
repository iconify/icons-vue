<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="h06uhqrfa"/><path class="ckfmts5is"/><path class="yw2g6ybff"/><path class="l2hvd9brx"/><circle class="fpn-48loo"/><circle class="fmh5sjb2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dailyart" /></template>
<style>
.ckfmts5is {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.547 22.235v20.336M21.09 29.013v3.728c-4.8 0-12.088 6.27-12.088 9.83");
}

.fmh5sjb2a {
  cx: 24.43px;
  cy: 17.68px;
  r: 0.75px;
  fill: currentColor;
}

.fpn-48loo {
  cx: 18.075px;
  cy: 17.68px;
  r: 0.75px;
  fill: currentColor;
}

.h06uhqrfa {
  width: 13.557px;
  height: 19.545px;
  x: 14.99px;
  y: 9.468px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 6.779px;
}

.l2hvd9brx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.029 22.178c.263.874 2.523.933 2.895 0m-2.895-4.848c-.283-.874-2.712-.933-3.112 0m9.263 0c-.283-.874-2.712-.933-3.112 0m-3.915 7.136a3.16 3.16 0 0 0 2.324.763a3.18 3.18 0 0 0 2.407-.89");
}

.yw2g6ybff {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 42.57s-2.937-8.981-7.642-8.981V16.21A10.78 10.78 0 0 0 24.077 5.43a10.78 10.78 0 0 0-10.782 10.781v17.378C9.737 34.888 6.008 39.972 5.5 42.57");
}

</style>
