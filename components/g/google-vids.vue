<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="tqs1xabqz"/><path class="rhfq0usew"/><path class="h5881_b4p"/><rect class="tqs1xabqz"/><path class="xat44hbrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:google-vids" /></template>
<style>
.h5881_b4p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.31 38.985a6.5 6.5 0 0 1-6.06-6.485v-17a6.5 6.5 0 0 1 6.06-6.485");
}

.rhfq0usew {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.34 33.568a5.5 5.5 0 0 1-3.92-3.958c-.17-.67-.17-1.482-.17-3.11v-5c0-1.627 0-2.44.17-3.11a5.5 5.5 0 0 1 3.92-3.957");
}

.tqs1xabqz {
  width: 26.5px;
  height: 38px;
  x: 15.25px;
  y: 5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 8px;
  ry: 8px;
}

.xat44hbrs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.911 22.05c1.008.547 1.511.82 1.72 1.156a1.5 1.5 0 0 1 0 1.588c-.209.335-.713.609-1.72 1.156l-4.631 2.517c-.932.507-1.398.76-1.778.76a1.5 1.5 0 0 1-1.321-.785C24 28.108 24 27.577 24 26.517v-5.034c0-1.06 0-1.59.181-1.925a1.5 1.5 0 0 1 1.321-.786c.38 0 .846.254 1.778.76z");
}

</style>
