<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><circle class="m3zvxll1f"/><path class="cah7mhbav"/><circle class="fcxtc4blm"/><path class="y4g19actv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:a99" /></template>
<style>
.cah7mhbav {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.28 29.38a4.35 4.35 0 0 0 3.88 1.76h.36a4.75 4.75 0 0 0 4.76-4.76v-4.76");
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

.fcxtc4blm {
  cx: 30.48px;
  cy: 21.62px;
  r: 4.76px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.m3zvxll1f {
  cx: 17.52px;
  cy: 21.62px;
  r: 4.76px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.y4g19actv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.25 29.38a4.35 4.35 0 0 0 3.88 1.76h.35a4.74 4.74 0 0 0 4.76-4.76v-4.76");
}

</style>
