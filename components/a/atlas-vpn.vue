<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xjzsi6bqf"/><circle class="g3n5u7b-r"/><path class="dukzezenl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:atlas-vpn" /></template>
<style>
.dukzezenl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 23.997A18.503 18.503 0 1 0 23.997 42.5H42.5z");
}

.g3n5u7b-r {
  cx: 17.543px;
  cy: 32.172px;
  r: 4.331px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xjzsi6bqf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.024 31.338a10.025 10.025 0 0 1 19.985 1.136l.002 10.024M6.187 29.039q-.024-.414-.024-.835a14.295 14.295 0 1 1 28.59 0l.003 14.294");
}

</style>
