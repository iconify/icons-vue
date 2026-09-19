<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wg1n0rgwn"/><circle class="lowmy9_bj"/><path class="nrkmu8b1a"/><circle class="vy5irpb0q"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:droidify" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.lowmy9_bj {
  cx: 20.975px;
  cy: 21.502px;
  r: 0.75px;
  fill: currentColor;
}

.nrkmu8b1a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m31.125 16.338l2.363-2.364");
}

.vy5irpb0q {
  cx: 27.025px;
  cy: 21.502px;
  r: 0.75px;
  fill: currentColor;
}

.wg1n0rgwn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.31 30.069a10.32 10.32 0 0 0 2.058-6.201C34.368 18.142 29.726 13.5 24 13.5s-10.368 4.642-10.368 10.368c0 2.325.766 4.471 2.058 6.2m1.185-13.73l-2.363-2.364M24 27.592V36.5m-4.454-4.454L24 36.5l4.454-4.454");
}

</style>
