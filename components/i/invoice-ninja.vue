<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yuu8q4ues"/><rect class="s4hx9gwkm"/><path class="ozw87q3cc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:invoice-ninja" /></template>
<style>
.ozw87q3cc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 15.527s16.821 4.408 19.5 4.408c2.475 0 19.5-4.408 19.5-4.408m-15.698 10.69L43.5 15.528m-39-.001l15.67 10.67M4.5 32.492s16.821-7.319 19.5-7.319c2.475 0 19.5 7.319 19.5 7.319");
}

.s4hx9gwkm {
  width: 39px;
  height: 19.544px;
  x: 4.5px;
  y: 14.228px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1px;
  ry: 1px;
}

.yuu8q4ues {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.996 24.053a2.603 2.603 0 0 1-2.452-2.608c0-1.442 1.16-2.612 2.592-2.612s2.593 1.17 2.593 2.612c0 .289-.048.575-.14.849m-19.177-.001a2.6 2.6 0 0 1-.14-.848a2.6 2.6 0 0 1 2.592-2.612h0a2.6 2.6 0 0 1 2.592 2.612a2.603 2.603 0 0 1-2.454 2.608");
}

</style>
