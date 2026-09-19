<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ogtkm36pn"/><path class="xi9i8tbkg"/><circle class="esvmngfga"/><circle class="afy5zroht"/><path class="fsz8eacua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:happyapk-app" /></template>
<style>
.afy5zroht {
  cx: 32.25px;
  cy: 19.355px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.esvmngfga {
  cx: 15.75px;
  cy: 19.355px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.fsz8eacua {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.69 26.231s3.96 4.082 10.31 4.082s10.31-4.082 10.31-4.082");
}

.ogtkm36pn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5c-2.216 0-4 1.784-4 4v29c0 2.216 1.784 4 4 4h21v-8c0-2.216 1.784-4 4-4h8v-21c0-2.216-1.784-4-4-4z");
}

.xi9i8tbkg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 30.5v3l-9 9h-3");
}

</style>
