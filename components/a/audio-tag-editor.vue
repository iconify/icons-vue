<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="ozijpvugs"/><path class="po_xykkbz"/><circle class="cwbyu_bgy"/><path class="vjandjdmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:audio-tag-editor" /></template>
<style>
.cwbyu_bgy {
  cx: 35.182px;
  cy: 12.819px;
  r: 2.285px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ozijpvugs {
  cx: 24.142px;
  cy: 23.859px;
  r: 9.71px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.po_xykkbz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.175 8.07L26.969 5.613a4.08 4.08 0 0 0-3.837 1.081L6.169 23.657a2.285 2.285 0 0 0 0 3.23l14.943 14.944a2.285 2.285 0 0 0 3.231 0l16.963-16.963a4.08 4.08 0 0 0 1.08-3.837L39.93 10.825a3.73 3.73 0 0 0-2.756-2.756Z");
}

.vjandjdmo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.61 27.793a2.285 2.285 0 1 1-4.57 0a2.285 2.285 0 0 1 4.57 0m0 0V17.64m0 .002a5.14 5.14 0 0 1 5.14 5.14");
}

</style>
