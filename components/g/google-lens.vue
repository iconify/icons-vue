<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="a34-23beg"/><circle class="vscp21boi"/><path class="d4m_gzb7n"/><path class="g8wj5lwpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:google-lens" /></template>
<style>
.a34-23beg {
  cx: 36.351px;
  cy: 36.333px;
  r: 4.111px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.d4m_gzb7n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 34.072a8.43 8.43 0 0 0 8.428 8.428H24v-4.111l-10.303-.026c-2.262 0-4.086-2.104-4.086-4.6V29.14H5.5zm28.778-20.35c2.26 0 4.11 2.13 4.11 4.625v7.709H42.5v-8.017a8.43 8.43 0 0 0-8.428-8.428h-2.878");
}

.g8wj5lwpe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.111 5.5H19.89l-3.083 4.111h-2.878A8.43 8.43 0 0 0 5.5 18.04v4.933h4.111v-4.625c0-2.495 1.85-4.625 4.111-4.625h20.556z");
}

.vscp21boi {
  cx: 24.018px;
  cy: 26.056px;
  r: 6.167px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
