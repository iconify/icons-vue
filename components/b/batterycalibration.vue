<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="ugmp5_bll"/><path class="n7zzxc1za"/><rect class="n5w9babge"/><path class="ijrfpfsqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:batterycalibration" /></template>
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

.ijrfpfsqd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.37 18.22zl-4.98 10.35l7.82-2.2l-4.99 8.85l4.99-8.85");
}

.n5w9babge {
  width: 13.84px;
  height: 24.96px;
  x: 17.08px;
  y: 14.24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1px;
}

.n7zzxc1za {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.95 12.31V9.25h-6.79V24H2.5m25.55-11.69V9.25h6.79V24H45.5");
}

.ugmp5_bll {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.98 12.31h1.93v1.93h-1.93zm8.1 0h1.93v1.93h-1.93z");
}

</style>
