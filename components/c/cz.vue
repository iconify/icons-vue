<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="adghcxrdt"/><path class="klhug2pfu"/><ellipse transform="rotate(-60 28.687 24)" class="g1rc2vb9x"/><path class="f_e6_fbrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cz" /></template>
<style>
.adghcxrdt {
  cx: 30.038px;
  cy: 21.141px;
  r: 7.329px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.f_e6_fbrc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.457 22.1v.024a1.93 1.93 0 0 1-1.93 1.93h0a1.93 1.93 0 0 1-1.929-1.93v-1.966a1.93 1.93 0 0 1 1.93-1.93h0a1.93 1.93 0 0 1 1.93 1.93v.024m1.162-1.953h3.858l-3.858 5.824h3.858");
}

.g1rc2vb9x {
  cx: 28.687px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 17.993px;
  ry: 12.103px;
}

.klhug2pfu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.026 28.188a12.2 12.2 0 0 1-10.25 5.55c-6.784 0-12.276-5.492-12.276-12.261C5.5 14.693 10.992 9.2 17.776 9.2c4.053 0 7.65 1.967 9.883 5.007");
}

</style>
