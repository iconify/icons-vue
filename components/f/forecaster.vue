<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="agete9vnq"/><circle class="cpk0fnbgt"/><path class="c8bbfrbyx"/><path class="p59spd2ll"/><path class="c3z-o9-yd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:forecaster" /></template>
<style>
.agete9vnq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.659 8.271a3.303 3.303 0 0 0-4.189 3.187c-3.533-.706-3.533 4.24-.707 4.24h7.78a2.9 2.9 0 0 0 1.995-.686");
}

.c3z-o9-yd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m20.773 40.207l15.948-14.988l6.609 8.201");
}

.c8bbfrbyx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.22 2.72a21.5 21.5 0 0 1-21.5 21.5m2.632 10.486l5.377-6.015L25.39 45.5");
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.p59spd2ll {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m13.431 31.789l10.78-13.139l8 10.808");
}

</style>
