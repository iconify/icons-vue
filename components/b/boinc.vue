<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="j5c5phb-q"/><path class="coqgi-ato"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:boinc" /></template>
<style>
.coqgi-ato {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.5 5.5l7.33 7.33m19.59-2.19a15.81 15.81 0 0 0-19.59 2.19m24.53 19.59a15.81 15.81 0 0 0-2.19-19.59h0L42.5 5.5M15.58 37.36a15.81 15.81 0 0 0 19.59-2.19h0l7.33 7.33M10.64 15.58a15.81 15.81 0 0 0 2.19 19.59h0L5.5 42.5");
}

.j5c5phb-q {
  cx: 24px;
  cy: 24px;
  r: 8.57px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
