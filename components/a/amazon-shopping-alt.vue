<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="mem18ybbx"/><path class="xhhfm4bls"/><rect class="rwqcrnbsz"/><path class="wvn0qbb7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:amazon-shopping-alt" /></template>
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

.mem18ybbx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.28 29.7c1.113-.45 3.092-1.048 3.688-.326c.644.781-.17 2.477-.92 3.794");
}

.rwqcrnbsz {
  width: 4px;
  height: 5.3px;
  x: 32.905px;
  y: 20.175px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
}

.wvn0qbb7t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.164 22.175a2 2 0 0 1 2-2a2 2 0 0 1 2 2v3.3m-4-5.3v5.3m4-3.3a2 2 0 0 1 2-2a2 2 0 0 1 2 2v3.3m8.122-5.3h4l-4 5.3h4m-22.272-2a2 2 0 0 1-2 2a2 2 0 0 1-2-2v-1.3a2 2 0 0 1 2-2a2 2 0 0 1 2 2m0 3.3v-5.3m16.15 3.3a2 2 0 0 1-2 2a2 2 0 0 1-2-2v-1.3a2 2 0 0 1 2-2a2 2 0 0 1 2 2m0 3.3v-5.3m17.822 5.3v-3.3a2 2 0 0 0-2-2a2 2 0 0 0-2 2v3.3m0-3.3v-2");
}

.xhhfm4bls {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.798 30.223c1.759 1.397 6.954 3.535 12.488 3.535a17 17 0 0 0 10.167-3.08");
}

</style>
