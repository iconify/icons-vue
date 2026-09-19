<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="e1y_7pbfn"/><circle class="djmaeme8p"/><path class="z-qzekbrp"/><path class="mkkx1_odk"/><circle class="zjj5onq1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kizzy" /></template>
<style>
.djmaeme8p {
  cx: 33.767px;
  cy: 24.931px;
  r: 1.559px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.e1y_7pbfn {
  cx: 13.168px;
  cy: 35.968px;
  r: 1.559px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.mkkx1_odk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.322 20.592c2.145-.38 4.395-.877 5.854-1.767c4.512-2.753 13.578.542 7.666 10.185M16.274 5.834C6.123 3.459 5.055 14.41 10.346 17.09c1.613.816 2.943 2.123 4.628 4.022m6.994 8.262c-.967 1.32-1.806 3.773-1.898 7.587c-.118 4.901-10.517 9.658-12.584-.312");
}

.z-qzekbrp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.494 18.41c5.181 3.382.667 8.073 2.704 12.575c1.436-5.367 7.196-4.295 10.244-8.522c-5.59 1.949-7.187-4.105-12.948-4.053");
}

.zjj5onq1d {
  cx: 15.442px;
  cy: 11.602px;
  r: 1.559px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
