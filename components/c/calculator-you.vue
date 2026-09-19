<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="dh5nuddxy"/><circle class="khsgttbqg"/><circle class="elsmppbpr"/><circle class="oxml-db7v"/><path class="wj81xvbtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calculator-you" /></template>
<style>
.dh5nuddxy {
  cx: 14px;
  cy: 14px;
  r: 8.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.elsmppbpr {
  cx: 14px;
  cy: 34px;
  r: 8.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.khsgttbqg {
  cx: 34px;
  cy: 14px;
  r: 8.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.oxml-db7v {
  cx: 34px;
  cy: 34px;
  r: 8.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.wj81xvbtp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.5 35.5h5m-5-3h5M11.35 10L14 14l2.65-4M14 18v-4m-2.65 16v5.35a2.65 2.65 0 1 0 5.3 0V30M34 10a2.65 2.65 0 0 1 2.65 2.65v2.7A2.65 2.65 0 0 1 34 18h0a2.65 2.65 0 0 1-2.65-2.65v-2.7A2.65 2.65 0 0 1 34 10");
}

</style>
