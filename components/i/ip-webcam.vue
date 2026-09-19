<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><circle class="k4o_yjbkq"/><ellipse transform="rotate(-24.414 19.094 16.183)" class="ukyzb9bkc"/><circle class="b0smh1bld"/><circle class="ufbccybaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ip-webcam" /></template>
<style>
.b0smh1bld {
  cx: 30.792px;
  cy: 18px;
  r: 1.923px;
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

.k4o_yjbkq {
  cx: 24px;
  cy: 24px;
  r: 14px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ufbccybaq {
  cx: 34.075px;
  cy: 22.146px;
  r: 1.36px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ukyzb9bkc {
  cx: 19.094px;
  cy: 16.183px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.518px;
  ry: 1.88px;
}

</style>
