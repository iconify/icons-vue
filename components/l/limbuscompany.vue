<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="t_3d8p0yo"/><circle class="btv28cb8k"/><circle class="bwgndrboz"/><path class="akpjoppuk"/><path class="yz7llobpm"/><path class="uqiy32toa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:limbuscompany" /></template>
<style>
.akpjoppuk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.24 21.672c-.218-.037-8.078 0-8.078 0m8.84-.763v-5.772m-2.918-1.812V9.383h2.918");
}

.btv28cb8k {
  cx: 24.002px;
  cy: 21.672px;
  r: 2.378px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.bwgndrboz {
  cx: 24.002px;
  cy: 21.672px;
  r: 0.762px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.t_3d8p0yo {
  cx: 24.002px;
  cy: 21.672px;
  r: 8.84px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.uqiy32toa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.998 6.823h2.187v2.56M23.998 5.28H28.2V3.5h-8.4v1.78h4.202m2.183 1.543C26.84 5.933 28.2 5.28 28.2 5.28m4.164 19.254h1.984v3.183c-2.75 0-4.003 1.89-4.003 4.449v.735s3.24-.11 3.24 0v2.15h1.47l1.28 2.615L24 44.5l-12.335-6.834l1.28-2.614h1.47V32.9c0-.11 3.24 0 3.24 0v-.735c0-2.56-1.253-4.449-4.003-4.449v-3.183h1.984m17.949 10.519h-19.17m10.194 0l1.084 8.51m1.185-8.51l1.622 6.955m2.393-1.326l-1.927-5.629m3.533 4.739l-2.008-4.739m3.235 4.059l-1.983-4.059m3.492 3.224l-1.65-3.224");
}

.yz7llobpm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.002 6.823h-2.187v2.56m0-2.56C21.16 5.933 19.8 5.28 19.8 5.28m3.591 29.772l-1.084 8.51m-1.185-8.51L19.5 42.007m-2.393-1.326l1.927-5.629m-3.533 4.739l2.008-4.739m-3.235 4.059l1.983-4.059m-3.492 3.224l1.65-3.224m12.501-21.727V9.383h-2.918");
}

</style>
