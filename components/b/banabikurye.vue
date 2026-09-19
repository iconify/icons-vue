<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="m6ooytulm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:banabikurye" /></template>
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

.m6ooytulm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.622 16.5v11m0-2.309l4.888-5.024m-3.259 3.395l3.803 3.802m-22.108-4.539a2.76 2.76 0 0 1 2.75-2.75h0a2.76 2.76 0 0 1 2.75 2.75v1.788a2.76 2.76 0 0 1-2.75 2.75h0a2.76 2.76 0 0 1-2.75-2.75m0 2.887v-11m8.357 6.325a2.76 2.76 0 0 1 2.75-2.75h0a2.76 2.76 0 0 1 2.75 2.75v1.788a2.76 2.76 0 0 1-2.75 2.75h0a2.76 2.76 0 0 1-2.75-2.75m0 2.887v-11");
}

</style>
