<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hj0hggnop"/><path class="dl4qm6a2g"/><circle class="l06vbrlyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:greaderpro" /></template>
<style>
.dl4qm6a2g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 42.5h-8v-6.82a22.24 22.24 0 0 0-22.18-22.22H5.5v-8h6.82A30.18 30.18 0 0 1 42.5 35.68Z");
}

.hj0hggnop {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30 42.5h-7.95v-6.82A9.67 9.67 0 0 0 12.38 26H5.5v-8h6.82A17.66 17.66 0 0 1 30 35.68h0Z");
}

.l06vbrlyb {
  cx: 11.2px;
  cy: 36.8px;
  r: 5.7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
