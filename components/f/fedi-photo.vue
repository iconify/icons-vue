<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="zy730csxw"/><circle class="fafp-82wg"/><circle class="krrxw830s"/><path class="qm2hi-bvn"/><circle class="pf13ffb6d"/><path class="phdcysbau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fedi-photo" /></template>
<style>
.fafp-82wg {
  cx: 24px;
  cy: 36.15px;
  r: 4.685px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.krrxw830s {
  cx: 9.185px;
  cy: 30.742px;
  r: 4.685px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.pf13ffb6d {
  cx: 38.815px;
  cy: 30.742px;
  r: 4.685px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.phdcysbau {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.195 22.122l5.307 5.307M24 31.465v-6.776m-7.872-4.91l3.59-3.59l1.801 1.8l5.773-5.773l5.277 5.276");
}

.qm2hi-bvn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.805 22.122l-5.307 5.307");
}

.zy730csxw {
  cx: 24px;
  cy: 15.927px;
  r: 8.762px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
