<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ze0q22k4x"/><path class="hh1trhbii"/><circle class="jg2auacnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gmo-town-wifi" /></template>
<style>
.hh1trhbii {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.18 7.53c7.993-6.707 19.647-6.707 27.64 0m-22.948 5.792a14.2 14.2 0 0 1 18.255 0M19.436 18.96a7.1 7.1 0 0 1 9.128 0m11.906-8.78a21.5 21.5 0 0 1-18.344 35.238m-3.691-.652a21.5 21.5 0 0 1-9.638-5.564m-2.409-2.871A21.5 21.5 0 0 1 7.53 10.18");
}

.jg2auacnj {
  cx: 24px;
  cy: 24.599px;
  r: 1.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ze0q22k4x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.18 7.53c7.993-6.707 19.647-6.707 27.64 0");
}

</style>
