<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="xyj4kacvn"/><rect class="z55znit5r"/><path class="jmjjzac4m"/><rect class="zsog_hbpl"/><path class="ai83hqsuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:box-now" /></template>
<style>
.ai83hqsuo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.25 18.375h-3.296m3.296 0a2 2 0 1 1 0 4h-3.3v-8h3.3a2 2 0 1 1 0 4");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.jmjjzac4m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.95 33.625v-8l5.3 8v-8m16.1-11.25l-5.3 8m0-8l5.3 8");
}

.xyj4kacvn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m36.05 25.625l-2 8l-2-8l-2 8l-2-8");
}

.z55znit5r {
  width: 5.3px;
  height: 8px;
  x: 20px;
  y: 25.625px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.65px;
  ry: 2.65px;
}

.zsog_hbpl {
  width: 5.3px;
  height: 8px;
  x: 20px;
  y: 14.375px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.65px;
  ry: 2.65px;
}

</style>
