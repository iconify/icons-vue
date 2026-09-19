<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j98an1bqd"/><path class="v68t1unox"/><rect class="x310817lr"/><path class="f2k6jv9_y"/><circle class="w8uma_28a"/><path class="v7t28cbht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ditzo-zorg" /></template>
<style>
.f2k6jv9_y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.111 21.611h5.169l-5.169 6.849h5.169");
}

.j98an1bqd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4z");
}

.v68t1unox {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 28.46V18.121h2.326a4.523 4.523 0 0 1 4.524 4.524v1.292a4.523 4.523 0 0 1-4.524 4.523z");
}

.v7t28cbht {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.247 21.611v6.849m4.002-8.982v8.982m-1.357-6.849h1.34");
}

.w8uma_28a {
  cx: 19.247px;
  cy: 18.444px;
  r: 0.75px;
  fill: currentColor;
}

.x310817lr {
  width: 5.17px;
  height: 6.85px;
  x: 33.331px;
  y: 21.611px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.585px;
  ry: 2.585px;
}

</style>
