<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><circle class="og3tjkr2p"/><path class="hj1kadchm"/><path class="eslayrf5n"/><path class="pwgz91zaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:a30-day-fitness-challenge" /></template>
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

.eslayrf5n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.525 26.159a4.238 4.238 0 0 0 8.475 0V21.84a4.238 4.238 0 0 0-8.475 0Zm-6.247-2.157a3.2 3.2 0 0 0 3.197-3.198h0a3.2 3.2 0 0 0-3.197-3.197m0 12.789a3.2 3.2 0 0 0 3.197-3.197v0a3.2 3.2 0 0 0-3.197-3.197m-5.277 5.315c.884.74 1.837 1.08 3.978 1.08h1.299");
}

.hj1kadchm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.068 13.011a15.476 15.476 0 1 1-1.906 2.3");
}

.og3tjkr2p {
  cx: 12.014px;
  cy: 14.078px;
  r: 1.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.pwgz91zaw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14 18.672c.885-.738 1.84-1.074 3.98-1.068l1.3.003m-3.26 6.395h3.258");
}

</style>
