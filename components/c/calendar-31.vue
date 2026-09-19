<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fd56s_bhv"/><g class="y9tr6bcfx"><circle class="bybjau59l"/><circle class="se87bac5g"/><rect class="brxpxfbzn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calendar-31" /></template>
<style>
.brxpxfbzn {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  rx: 4px;
  ry: 4px;
}

.bybjau59l {
  cx: 32.5px;
  cy: 11px;
  r: 2.5px;
}

.fd56s_bhv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.238 34.778c1.104.926 2.297 1.35 4.975 1.35h.624a4 4 0 0 0 3.999-4h0a4 4 0 0 0-4-3.998m-5.6-6.666c1.107-.922 2.3-1.343 4.979-1.336l.622.004a4 4 0 0 1 4 3.999h0a4 4 0 0 1-4 3.999m-3.074 0h3.074m9.927-5.93l4-2.2m0 0v16");
}

.se87bac5g {
  cx: 15.5px;
  cy: 11px;
  r: 2.5px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
