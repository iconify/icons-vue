<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="i_c_bcbgc"/><path class="t2yud-bqp"/><path class="bsuhv7bvp"/><rect class="lvc6mfbpz"/><rect class="q1oi3ntwr"/><rect class="d2wi7-ggo"/><rect class="ufcjyccnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cinta" /></template>
<style>
.bsuhv7bvp {
  fill: none;
  stroke: currentColor;
  d: path("M33.269 36.275s-.178 3.763-3.763 3.763H24");
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.d2wi7-ggo {
  width: 3.381px;
  height: 2.56px;
  x: 22.309px;
  y: 34.041px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.783px;
}

.i_c_bcbgc {
  fill: none;
  stroke: currentColor;
  d: path("M14.731 36.275s.178 3.763 3.763 3.763H24");
}

.lvc6mfbpz {
  width: 13.227px;
  height: 3.063px;
  x: 17.386px;
  y: 29.142px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.738px;
}

.q1oi3ntwr {
  width: 3.381px;
  height: 2.56px;
  x: 17.231px;
  y: 34.041px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.783px;
}

.t2yud-bqp {
  fill: none;
  stroke: currentColor;
  d: path("M33.26 43.41V15.647a3.46 3.46 0 0 0-1.732-3l-5.796-3.346a3.46 3.46 0 0 0-3.464 0l-5.796 3.346a3.46 3.46 0 0 0-1.732 3v27.854");
}

.ufcjyccnx {
  width: 3.381px;
  height: 2.56px;
  x: 27.388px;
  y: 34.041px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.783px;
}

</style>
