<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yzl9rdxxs"/><path class="hqaaugb_c"/><circle class="pkmw_5_ik"/><circle class="vg0vo4bhn"/><circle class="fnoslegxg"/><circle class="h-d-jj0ew"/><path class="frxbgmbch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:heyfun" /></template>
<style>
.fnoslegxg {
  cx: 22.268px;
  cy: 16.224px;
  r: 2.222px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.frxbgmbch {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m34.589 11.604l4.859-4.858m-4.859 0l4.859 4.858");
}

.h-d-jj0ew {
  cx: 35.228px;
  cy: 27.571px;
  r: 2.222px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.hqaaugb_c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.086 29.793c0 7.018 5.689 12.707 12.707 12.707S42.5 36.81 42.5 29.793s-5.689-12.707-12.707-12.707");
}

.pkmw_5_ik {
  cx: 10.421px;
  cy: 37.641px;
  r: 3.426px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.vg0vo4bhn {
  cx: 12.342px;
  cy: 16.224px;
  r: 2.222px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yzl9rdxxs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.647 5.5c6.703 0 12.146 5.443 12.146 12.147v12.146H5.5V17.647C5.5 10.942 10.943 5.5 17.647 5.5");
}

</style>
