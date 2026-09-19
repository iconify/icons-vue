<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><circle class="wb4pm1bqq"/><circle class="fby0u-_yf"/><circle class="jt3mgibou"/><circle class="aszs0p1mb"/><circle class="g4a_k_b_z"/><circle class="ry88yfnka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:diceware" /></template>
<style>
.aszs0p1mb {
  cx: 14px;
  cy: 12px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-miterlimit: 3.596;
}

.fby0u-_yf {
  cx: 34px;
  cy: 24px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-miterlimit: 3.596;
}

.g4a_k_b_z {
  cx: 14px;
  cy: 24px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-miterlimit: 3.596;
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.jt3mgibou {
  cx: 34px;
  cy: 36px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-miterlimit: 3.596;
}

.ry88yfnka {
  cx: 14px;
  cy: 36px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-miterlimit: 3.596;
}

.wb4pm1bqq {
  cx: 34px;
  cy: 12px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-miterlimit: 3.596;
}

</style>
