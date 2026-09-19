<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="e4x41wbpn"/><path class="ml6je83sf"/><path class="relldpw5b"/><path class="awgs1sbzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:allcast" /></template>
<style>
.awgs1sbzm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 21.677a12.997 12.997 0 0 1 12.997 12.997");
}

.e4x41wbpn {
  width: 37px;
  height: 25.227px;
  x: 5.5px;
  y: 9.447px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.682px;
}

.ml6je83sf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.102 38.553h17.796M5.5 30.675a4 4 0 0 1 4 3.999h0m-4-6.999a7 7 0 0 1 6.999 6.999h0M5.5 18.677a15.997 15.997 0 0 1 15.997 15.997");
}

.relldpw5b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 24.676a10 10 0 0 1 9.998 9.998h0");
}

</style>
