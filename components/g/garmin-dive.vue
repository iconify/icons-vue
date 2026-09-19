<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s15gkwbmm"/><circle class="c8c-a65gx"/><path class="aqrtfufjp"/><circle class="h0pi8obpw"/><path class="q2zirob_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:garmin-dive" /></template>
<style>
.aqrtfufjp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.176 8.115a2.68 2.68 0 0 0-2.82-2.678c-1.447.076-2.532 1.377-2.532 2.83v2.484A2.68 2.68 0 0 0 9.5 13.433h0c1.478 0 2.676-1.2 2.676-2.682H9.5");
}

.c8c-a65gx {
  cx: 9.5px;
  cy: 9.433px;
  r: 7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.h0pi8obpw {
  cx: 24.365px;
  cy: 34.883px;
  r: 3.244px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.q2zirob_l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.387 34.883h-2.778m-6.489 0h-1.155a7.18 7.18 0 0 0-7.178 7.178v.446M24.365 25.88a3.57 3.57 0 0 0 3.569 3.57h3.71a3.57 3.57 0 0 0 3.569-3.57v-1.824a5.556 5.556 0 0 0-5.556-5.556H19.073a5.556 5.556 0 0 0-5.556 5.556v1.825a3.57 3.57 0 0 0 3.57 3.568h3.71a3.57 3.57 0 0 0 3.568-3.568");
}

.s15gkwbmm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 15.176V38.5a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4H15.291");
}

</style>
