<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gegn7nugn"/><ellipse class="lp5ysqb2k"/><path class="zloj8n2ef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:datadex" /></template>
<style>
.gegn7nugn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.838 26.332a6.69 6.69 0 0 0-6.668-6.668a6.69 6.69 0 0 0-6.669 6.668v4.335a6.69 6.69 0 0 0 6.669 6.669a6.69 6.69 0 0 0 6.669-6.67m0 6.67V10.66m7.99 26.678V10.662h4.334A13.377 13.377 0 0 1 43.501 24a13.377 13.377 0 0 1-13.338 13.338Z");
}

.lp5ysqb2k {
  cx: 34.748px;
  cy: 23.873px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.301px;
  ry: 3.165px;
}

.zloj8n2ef {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.145 24h5.346m12.006 0h-5.342");
}

</style>
