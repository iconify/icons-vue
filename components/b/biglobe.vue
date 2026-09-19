<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><circle class="chm50nbzv"/><circle class="f75ymac1y"/><circle class="pl-pg73xo"/><circle class="dqfxtbcyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:biglobe" /></template>
<style>
.chm50nbzv {
  cx: 16.5px;
  cy: 11.536px;
  r: 4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.dqfxtbcyd {
  cx: 31.5px;
  cy: 11.536px;
  r: 1.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.f75ymac1y {
  cx: 31.5px;
  cy: 11.536px;
  r: 4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.pl-pg73xo {
  cx: 16.5px;
  cy: 11.536px;
  r: 1.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
