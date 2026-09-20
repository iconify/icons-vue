<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="mem18ybbx"/><path class="xhhfm4bls"/><rect class="hynlserts"/><rect class="ngzp5rb2y"/><path class="itlqpbbnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:amazon-photos" /></template>
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

.hynlserts {
  width: 4px;
  height: 5.3px;
  x: 20.505px;
  y: 20.175px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
}

.itlqpbbnl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.469 17.475v8m.001-3.3a2 2 0 0 1 2-2a2 2 0 0 1 2 2v3.3m17.666-.447a2.25 2.25 0 0 0 1.645.447h.449a1.324 1.324 0 0 0 1.322-1.325a1.324 1.324 0 0 0-1.322-1.325h-.897A1.324 1.324 0 0 1 36.01 21.5a1.324 1.324 0 0 1 1.322-1.325h.449a2.25 2.25 0 0 1 1.645.447M27.14 18.525v5.95a1 1 0 0 0 1 1h.3m-2.349-5.3h2.1m-19.743 3.3a2 2 0 0 0 2 2a2 2 0 0 0 2-2v-1.3a2 2 0 0 0-2-2a2 2 0 0 0-2 2m0-2v8");
}

.mem18ybbx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.28 29.7c1.113-.45 3.092-1.048 3.688-.326c.644.781-.17 2.477-.92 3.794");
}

.ngzp5rb2y {
  width: 4px;
  height: 5.3px;
  x: 30.05px;
  y: 20.175px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
}

.xhhfm4bls {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.798 30.223c1.759 1.397 6.954 3.535 12.488 3.535a17 17 0 0 0 10.167-3.08");
}

</style>
