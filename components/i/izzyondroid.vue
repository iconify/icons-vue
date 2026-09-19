<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pwdi-ru8u"/><path class="skorsob1a"/><path class="vw1q9bc_z"/><path class="cmfkmh4by"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:izzyondroid" /></template>
<style>
.cmfkmh4by {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.309 20.519l-1.889 1.829m-8.64-1.83l1.893 1.825m9.544 5.174a6.173 6.173 0 0 0-12.345 0Z");
}

.pwdi-ru8u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.145 6.048L20.973 17.54l13.66.022M17.196 23.38L5.607 41.723");
}

.skorsob1a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.634 17.562a12.6 12.6 0 0 1-5.01 24.161H5.608m7.205-11.514a12.6 12.6 0 0 1 5.01-24.161H41.84L31.578 22.292m-4.855 7.684l-7.421 11.747");
}

.vw1q9bc_z {
  fill: currentColor;
  d: path("M21.57 24.315a.75.75 0 1 1-.75.75a.75.75 0 0 1 .75-.75m5.247 0a.752.752 0 1 1-.004 0Z");
}

</style>
