<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="niypo6vhc"/><path class="zranco17z"/><ellipse transform="rotate(-89.69 23.945 13.729)" class="ohn3thd7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cube-escape-the-mill" /></template>
<style>
.niypo6vhc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.727 13.803L23.887 3.5L6.163 13.729l17.84 10.303z");
}

.ohn3thd7s {
  cx: 23.945px;
  cy: 13.729px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.701px;
  ry: 4.678px;
}

.zranco17z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.003 24.032L6.163 13.729v20.468L24.003 44.5zm17.724-10.229L24.003 24.032V44.5l17.724-10.229zm-24.281 3.678l12.998-7.504m-13.039-.024l13.08 7.552");
}

</style>
