<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="niypo6vhc"/><path class="hk1yyeiqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cube-escape-theatre" /></template>
<style>
.hk1yyeiqs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.003 24.032L6.163 13.729v20.468L24.003 44.5zm17.724-10.229L24.003 24.032V44.5l17.724-10.229zm-3.568-2.061L20.435 21.971m14.156-12.29L16.867 19.91M31.023 7.621L13.299 17.85M27.455 5.561L9.731 15.79");
}

.niypo6vhc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.727 13.803L23.887 3.5L6.163 13.729l17.84 10.303z");
}

</style>
