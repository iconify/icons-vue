<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="pd1y22bpi"/><path class="sefh9vqjp"/><path class="e6ucgnlgw"/><path class="do1c7wbgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:google-earth" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.do1c7wbgr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M44.7 18.168a6.4 6.4 0 0 1-1.905.281c-7.038 0-7.15-15.303-21.364-15.303a20.3 20.3 0 0 0-4.68.607");
}

.e6ucgnlgw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.384 10.355a12.23 12.23 0 0 1 8.637-3.863c12.716 0 15.587 18.674 25.035 18.674a6.06 6.06 0 0 0 4.425-2.083");
}

.pd1y22bpi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.458 32.963c-.748-3.332 1.208-7.124 4.909-7.124c8.965 0 10.984 14.662 22.9 14.662c5.887 0 9.773-4.795 9.773-4.795");
}

.sefh9vqjp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M2.504 24.003a9.096 9.096 0 0 1 9.17-9.278c12.237 0 12.924 18.549 25.625 18.549c4.448 0 6.742-2.695 7.914-5.755");
}

</style>
