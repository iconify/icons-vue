<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="s03fv-bua"/><circle class="tooj30n6l"/><path class="a9p7dfbvo"/><path class="r5-4j4usb"/><path class="aaomvu3tu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:callabike" /></template>
<style>
.a9p7dfbvo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m36.78 28.94l-5.84-14.09l-.28-1.66l1.22-.99");
}

.aaomvu3tu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m18.52 17.33l.98 3.24l3.74 8.81M16.5 17.55l4.37-.48");
}

.r5-4j4usb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.94 14.85L19.5 20.57l-8.28 8.51l12.02.3l8.86-11.73");
}

.s03fv-bua {
  cx: 36.78px;
  cy: 28.94px;
  r: 6.72px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.tooj30n6l {
  cx: 11.22px;
  cy: 29.08px;
  r: 6.72px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
