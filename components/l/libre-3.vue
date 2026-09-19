<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y8_9yrfrm"/><path class="auti8tbmp"/><path class="tmany-bhj"/><circle class="vi_nxfq0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:libre-3" /></template>
<style>
.auti8tbmp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.5 12.75a3.5 3.5 0 0 1 7 0v6.5a3.5 3.5 0 0 1-7 0ZM39.15 38.5a2 2 0 0 0 2-2h0a2 2 0 0 0-2-1.999m0 7.999a2 2 0 0 0 2-2h0a2 2 0 0 0-2-2");
}

.tmany-bhj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.85 41.825a3.4 3.4 0 0 0 2.489.675h.812m-3.301-7.332a3.4 3.4 0 0 1 2.49-.668l.811.002m-2.037 3.999h2.037");
}

.vi_nxfq0r {
  cx: 38.5px;
  cy: 38.5px;
  r: 7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.y8_9yrfrm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.432 43.326a21.486 21.486 0 1 1 9.894-9.893");
}

</style>
