<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="eod0sebeq"/><circle class="wlskugb4y"/><circle class="wjs-2cb2c"/><circle class="n5682jb5s"/><path class="nzwa8mbuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:japan-post-bank-passbook" /></template>
<style>
.eod0sebeq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.057 12.675H40.76c-.912 0-1.41.892-1.56 2l-2.526 18.642c-.15 1.108-1.163 2-2.27 2H5.99c-1.108 0-1.88-.892-1.729-2l2.525-18.642c.15-1.108 1.163-2 2.271-2");
}

.n5682jb5s {
  cx: 30.276px;
  cy: 29.555px;
  r: 1.813px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.nzwa8mbuu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.871 27.155v4.334c0 2.062-1.587 3.837-2.303 3.837M10.185 14.287h26.063c.554 0 .855.437.788 1l-.125 1.055c-.067.563-.658 1-1.212 1H9.636c-.554 0-.872-.443-.788-1l.125-1.055c.08-.583.658-1 1.212-1m30.574-1.613c1.562 0 1.796 3.07 1.796 3.07L43.753 30.2c.084 1.334-1.327 2.718-2.906 2.718h-3.9");
}

.wjs-2cb2c {
  cx: 21.591px;
  cy: 29.555px;
  r: 1.813px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.wlskugb4y {
  cx: 25.871px;
  cy: 23.544px;
  r: 3.45px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
