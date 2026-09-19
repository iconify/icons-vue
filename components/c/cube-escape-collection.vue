<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="niypo6vhc"/><path class="c62c4hb2x"/><path class="dq65___ra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cube-escape-collection" /></template>
<style>
.c62c4hb2x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.003 24.032L6.163 13.729v20.468L24.003 44.5zm17.724-10.229L24.003 24.032V44.5l17.724-10.229zm-21.674-8.09c1.994 5.672 6.142 5.612 9.389 5.904c5.92.533 6.595 5.233 6.595 5.233m-21.64-7.873c1.2 5.44 4.184 7.966 9.337 7.418c4.267-.455 6.92-1.17 9.886 2.086");
}

.dq65___ra {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.862 22.382c-2.04-2.223-4.44-.8-7.361-.95");
}

.niypo6vhc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.727 13.803L23.887 3.5L6.163 13.729l17.84 10.303z");
}

</style>
