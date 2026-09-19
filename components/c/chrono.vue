<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="skryuubpv"/><path class="re95pacjq"/><path class="na5980bri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:chrono" /></template>
<style>
.na5980bri {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 17v8l4 4");
}

.re95pacjq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.485 15.515a12 12 0 1 0 0 16.97");
}

.skryuubpv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 45.5c11.874 0 21.5-9.626 21.5-21.5S35.874 2.5 24 2.5S2.5 12.126 2.5 24S12.126 45.5 24 45.5");
}

</style>
