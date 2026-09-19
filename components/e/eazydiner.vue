<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="la2klucnb"/><circle class="v2sa847jv"/><path class="f4phaqq4i"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:eazydiner" /></template>
<style>
.f4phaqq4i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.093 20.767v6.077m7.062 0v-3.783a2.293 2.293 0 0 0-2.294-2.293h0a2.293 2.293 0 0 0-2.293 2.293m.001 3.783v-6.077m11.354 4.92a2.29 2.29 0 0 1-1.992 1.157h0a2.293 2.293 0 0 1-2.293-2.293v-1.49a2.293 2.293 0 0 1 2.293-2.294h0a2.293 2.293 0 0 1 2.293 2.293v.746h-4.586m-12.052-.746a2.293 2.293 0 0 0-2.293-2.292h0A2.293 2.293 0 0 0 11 23.06v1.49a2.293 2.293 0 0 0 2.293 2.293h0a2.293 2.293 0 0 0 2.293-2.293m0 2.294v-9.172");
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

.la2klucnb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.707 23.06A2.293 2.293 0 0 1 37 20.769h0m-2.293-.002v6.077");
}

.v2sa847jv {
  cx: 18.093px;
  cy: 17.959px;
  r: 0.803px;
  fill: currentColor;
}

</style>
