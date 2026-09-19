<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m77sn-4vc"/><rect class="a5ix7ub7s"/><rect class="ft98k7bhc"/><rect class="c8ui7b8hq"/><path class="yyx8u9bkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:corona-scanner" /></template>
<style>
.a5ix7ub7s {
  width: 7.054px;
  height: 7.054px;
  x: 14.986px;
  y: 14.986px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.784px;
}

.c8ui7b8hq {
  width: 7.054px;
  height: 7.054px;
  x: 25.959px;
  y: 14.986px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.784px;
}

.ft98k7bhc {
  width: 7.054px;
  height: 7.054px;
  x: 14.986px;
  y: 25.959px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.784px;
}

.m77sn-4vc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 20.473V9.5h-29v10.973a3.527 3.527 0 0 1 0 7.054V38.5h29V27.527a3.527 3.527 0 0 1 0-7.054");
}

.yyx8u9bkx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.311 28.311h2.351v2.351h-2.351zm2.351-2.352h2.351v2.351h-2.351zm0 4.703h2.351v2.351h-2.351zm-4.703-4.703h2.351v2.351h-2.351zm0 4.703h2.351v2.351h-2.351zM12 5.5H5.5V12m37 0V5.5H36m0 37h6.5V36m-37 0v6.5H12");
}

</style>
