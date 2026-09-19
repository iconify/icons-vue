<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><circle class="pfdnitkma"/><path class="hkf-5xdai"/><circle class="cqikeebnw"/><path class="r8_sz1uzn"/><path class="rvqyq422r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:color-switch" /></template>
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

.cqikeebnw {
  cx: 24px;
  cy: 20.002px;
  r: 3.883px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.hkf-5xdai {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.17 24h6.33m-43 0h6.33M24 39.17v6.33m0-43v6.33");
}

.pfdnitkma {
  cx: 24px;
  cy: 24px;
  r: 15.17px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.r8_sz1uzn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.864 27.168a2.51 2.51 0 1 1-3.727 0");
}

.rvqyq422r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.68 22.812a3.202 3.202 0 1 1-5.36 0");
}

</style>
