<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="bll073oob"/><path class="w65g-ebbh"/><path class="hk5ziu8bk"/><path class="ipvbzdb2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:i-cant-wake-up" /></template>
<style>
.bll073oob {
  cx: 23.932px;
  cy: 24.419px;
  r: 18.432px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.hk5ziu8bk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.521 31.889a12.99 12.99 0 1 0 16.977-18.918m-3.729-1.447a12.978 12.978 0 0 0-15.091 16.814m4.068-22.611A7.487 7.487 0 0 0 5.428 15.813m3.943 22.193a3.564 3.564 0 0 0 5.658 4.22M32.254 5.727a7.487 7.487 0 0 1 10.318 10.086m-3.943 22.193a3.564 3.564 0 0 1-5.658 4.22");
}

.ipvbzdb2c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.664 20.209a7.5 7.5 0 0 0 4.137 11.17m4 .106a7.5 7.5 0 0 0 5.26-4.768m.279-4A7.5 7.5 0 0 0 26 16.992m-4 .014a7.4 7.4 0 0 0-1.365.518m5.857 6.504A2.5 2.5 0 0 0 26 22.721m-4 .002a2.5 2.5 0 0 0 1.48 3.938");
}

.w65g-ebbh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 13.217v11l3.5 4");
}

</style>
