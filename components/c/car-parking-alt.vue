<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vizz3-bsk"/><rect class="lscsb5b7t"/><circle class="foj5eda3i"/><path class="zuf083b9t"/><circle class="ux7ygesjb"/><path class="a-98acbmj"/><rect class="qp8sfjlgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:car-parking-alt" /></template>
<style>
.a-98acbmj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.782 38.022v1.391m10.436-1.391v1.391");
}

.foj5eda3i {
  cx: 19.106px;
  cy: 35.413px;
  r: 0.75px;
  fill: currentColor;
}

.lscsb5b7t {
  width: 15.219px;
  height: 5.653px;
  x: 16.39px;
  y: 32.369px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.739px;
  ry: 1.739px;
}

.qp8sfjlgh {
  width: 33px;
  height: 39px;
  x: 7.5px;
  y: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.ux7ygesjb {
  cx: 28.894px;
  cy: 35.413px;
  r: 0.75px;
  fill: currentColor;
}

.vizz3-bsk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.778 24.353V8.587h5.161c2.918 0 5.283 2.37 5.283 5.295s-2.365 5.295-5.283 5.295h-5.161");
}

.zuf083b9t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m18.13 32.369l1.022-3.998c.171-.67.878-1.22 1.57-1.22h6.555c.693 0 1.4.55 1.572 1.22l1.021 3.998");
}

</style>
