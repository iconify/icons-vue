<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ufd_vcx9g"/><path class="pwpnmtbkm"/><path class="dxm3ywqso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:esim-me" /></template>
<style>
.dxm3ywqso {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.313 30.734a3.124 3.124 0 1 1 6.249 0v5.155m8.964-1.576a3.124 3.124 0 0 1-5.84-1.548v-2.03a3.124 3.124 0 1 1 6.25 0v1.015h-6.25M26.677 5.5V18M30 17.986V5.5L36.25 18L42.5 5.519V18m-27.18-1.369c.766.998 1.728 1.37 3.065 1.37h1.85a3.12 3.12 0 0 0 3.119-3.125a3.12 3.12 0 0 0-3.119-3.125h-2.041a3.12 3.12 0 0 1-3.121-3.124c0-1.726 1.4-3.126 3.128-3.126h1.84c1.338 0 2.299.371 3.065 1.37M11.34 16.424a3.125 3.125 0 0 1-5.84-1.548v-2.031a3.125 3.125 0 1 1 6.25 0v1.015H5.5");
}

.pwpnmtbkm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.065 30.734a3.124 3.124 0 1 1 6.249 0v5.155m-6.249-8.279v8.28");
}

.ufd_vcx9g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 21h-37v21.5H34l8.5-8.5z");
}

</style>
