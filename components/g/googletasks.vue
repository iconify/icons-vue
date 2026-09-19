<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d_xrxcc9a"/><rect class="ecgdubc4s"/><path class="pt_u7_bea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:googletasks" /></template>
<style>
.d_xrxcc9a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.167 32.218c1.541 6.494 7.373 11.328 14.339 11.328h4.988c4.073 0 7.755-1.65 10.421-4.317a14.67 14.67 0 0 0 3.918-7.01");
}

.ecgdubc4s {
  width: 39px;
  height: 34.465px;
  x: 4.5px;
  y: 5.454px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 16.779px;
  ry: 16.779px;
}

.pt_u7_bea {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m16.064 22.686l5.027 5.027a.907.907 0 0 0 1.283 0l11.15-11.15");
}

</style>
