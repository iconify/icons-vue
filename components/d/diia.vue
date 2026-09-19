<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="vbsrltpmr"/><circle class="dpb4x8boe"/><path class="jzrjwpbhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:diia" /></template>
<style>
.dpb4x8boe {
  cx: 26.288px;
  cy: 19.312px;
  r: 0.75px;
  fill: currentColor;
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.jzrjwpbhj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.548 28.006s-1.183 1.286-1.92 1.286h0a.993.993 0 0 1-.923-1.309l1.25-6.314H24.08M20.692 31.5v-4.104H10.357V31.5m8.693-4.104V16.5h-6.38c0 3.172.597 7.873-1.343 10.896");
}

.vbsrltpmr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.632 29V19h-3.274a3.359 3.359 0 0 0 0 6.717h3.274m-3.273 0l-3.274 3.28");
}

</style>
