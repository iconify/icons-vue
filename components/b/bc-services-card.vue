<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="mejnhzb5l"/><path class="b2g0pzblf"/><circle class="cyoibd7je"/><path class="jvtdpcc2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bc-services-card" /></template>
<style>
.b2g0pzblf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.579 22.963c-2.643 2.456-2.014 9.036-2.014 9.036H22.41s.658-6.79-2.196-9.2");
}

.cyoibd7je {
  cx: 15.842px;
  cy: 19.369px;
  r: 3.369px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.jvtdpcc2v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.191 21.283H38.5m-12.309-2.984H38.5m-12.309 5.969H38.5m-12.344 2.984h12.31M26.32 30.237h6.58");
}

.mejnhzb5l {
  width: 39px;
  height: 29px;
  x: 4.5px;
  y: 9.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
