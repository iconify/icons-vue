<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="imu-ntbes"/><path class="j5yk-abto"/><path class="hp6-8bbsv"/><path class="utn25qz1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:amboss-qbank" /></template>
<style>
.hp6-8bbsv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m38.44 31.01l-11.43-19.8l-14.6 25.28L9.23 42h22.1");
}

.imu-ntbes {
  cx: 36.964px;
  cy: 37.845px;
  r: 7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.j5yk-abto {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m39.614 41.845l-2.65-2.618m0-5.382za2.65 2.65 0 0 1 2.65 2.65v2.7a2.65 2.65 0 1 1-5.3 0v-2.7a2.65 2.65 0 0 1 2.65-2.65M33.03 32.05L27.23 22");
}

.utn25qz1p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.09 36.49H6.39L24 6");
}

</style>
