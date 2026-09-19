<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tw26e2_6c"/><circle class="h_mgq373y"/><circle class="ghed1ac7b"/><circle class="wm830cc3l"/><path class="iv04wcbub"/><circle class="lxdowwbsg"/><path class="ycy9v4bid"/><path class="i9clfwm2k"/><circle class="xmowibcql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:digiturk-online" /></template>
<style>
.ghed1ac7b {
  cx: 13.675px;
  cy: 10.495px;
  r: 0.75px;
  fill: currentColor;
}

.h_mgq373y {
  cx: 17.772px;
  cy: 14.398px;
  r: 2.088px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.iv04wcbub {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.812 16.486V12.31");
}

.lxdowwbsg {
  cx: 21.812px;
  cy: 10.495px;
  r: 0.75px;
  fill: currentColor;
}

.tw26e2_6c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.722 38.49a8.355 8.355 0 1 0-4.72 1.462v-7.143M8.26 9.88a3.303 3.303 0 0 1 3.303 3.303h0a3.303 3.303 0 0 1-3.304 3.303h0m5.416 0V12.31");
}

.wm830cc3l {
  cx: 17.723px;
  cy: 19.332px;
  r: 1.587px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xmowibcql {
  cx: 24.001px;
  cy: 30.263px;
  r: 0.75px;
  fill: currentColor;
}

.ycy9v4bid {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.121 16.486v-5.625m0 1.449h1.234m5.811 0v2.088a2.088 2.088 0 0 1-4.176 0V12.31m8.217 0a2.09 2.09 0 0 0-2.088 2.088v2.088m3.628 0V9.879m.475 4.519l2.519-2.088m-2.519 2.088l2.519 2.088");
}

</style>
