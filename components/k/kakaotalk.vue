<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="awv7lacly"/><circle class="d33wh1b5o"/><circle class="oawtoth3w"/><circle class="j4_9z5lcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kakaotalk" /></template>
<style>
.awv7lacly {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 6C13.23 6 4.5 12.93 4.5 21.46c0 5.39 3.5 10.13 8.79 12.89l-1.76 7.06a.46.46 0 0 0 .68.51L21 36.7a24 24 0 0 0 3 .2c10.77 0 19.5-6.91 19.5-15.44S34.77 6 24 6");
}

.d33wh1b5o {
  cx: 23.91px;
  cy: 21.46px;
  r: 2.71px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.j4_9z5lcd {
  cx: 14.18px;
  cy: 21.46px;
  r: 2.71px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.oawtoth3w {
  cx: 33.65px;
  cy: 21.46px;
  r: 2.71px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
