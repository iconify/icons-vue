<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s_qlj_fwh"/><circle class="a_f87pbuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:imgurviewer" /></template>
<style>
.a_f87pbuk {
  cx: 17.99px;
  cy: 9.434px;
  r: 4.934px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.s_qlj_fwh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.455 41.703L34.944 6.588h-8.18L22.02 22.464V17.14h-8.18v25.11a1.25 1.25 0 0 0 1.25 1.25h6.952a2.52 2.52 0 0 0 2.413-1.797");
}

</style>
