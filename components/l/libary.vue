<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dh3whdb5w"/><path class="ph61ddhrd"/><path class="fh85-e4xz"/><path class="k4in53bfv"/><path class="gcx979b0s"/><ellipse class="zjzn9pned"/><circle class="ol1cj-b-t"/><circle class="hurlwbcml"/><path class="be6s7x2ps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:libary" /></template>
<style>
.be6s7x2ps {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.178 43.5h25.644V17.856c0-7.486-5.28-13.35-12.822-13.356s-12.822 5.877-12.822 13.356Z");
}

.dh3whdb5w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m28.192 35.499l3.556 2.164l-1.12-16.189m-9.833 19.889h1.602v-1.069l3.206-1.068v2.137h1.602");
}

.fh85-e4xz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.839 15.72c-1.925 3.241-5.234 4.187-8.954 5.853c0 0 1.431 6.628 3.521 6.63c1.793 0 2.629-3.285 2.629-3.285");
}

.gcx979b0s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.315 24.267c4.444-1.16 6.476-5.1 7.846-8.548h5.678c1.84 3.814 4.171 6.818 7.846 8.548");
}

.hurlwbcml {
  cx: 34.685px;
  cy: 24.267px;
  r: 0.379px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.k4in53bfv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.137 20.641s.03 2.765 1.285 3.152c1.732.535 6.864-5.406 6.864-5.406l-.094 17.112l-2.59 3.727");
}

.ol1cj-b-t {
  cx: 13.315px;
  cy: 24.267px;
  r: 0.379px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ph61ddhrd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.406 28.202l.991 12.093c3.388-5.373 2.869-11.295 4.12-17.88");
}

.zjzn9pned {
  cx: 24px;
  cy: 13.048px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.603px;
  ry: 2.137px;
}

</style>
