<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="oyixtmoxh"/><path class="xigr4jbxt"/><circle class="kbp7eqb3r"/><path class="vv899zbzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kwgt-pro" /></template>
<style>
.kbp7eqb3r {
  cx: 16.922px;
  cy: 40.511px;
  r: 2.989px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.oyixtmoxh {
  width: 5.978px;
  height: 28.394px;
  x: 13.933px;
  y: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.196px;
  ry: 1.196px;
}

.vv899zbzj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.911 40.511h14.156V43.5m-4.817-1.02v-1.969");
}

.xigr4jbxt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.469 4.5h-.598a4.78 4.78 0 0 0-4.782 4.782v3.173a.6.6 0 0 1-.196.442l-5.407 4.915a1.196 1.196 0 0 0 0 1.77l5.407 4.915a.6.6 0 0 1 .196.442v3.173a4.78 4.78 0 0 0 4.782 4.782h.598c.33 0 .598-.267.598-.597v-9.518c0-.317-.126-.621-.35-.845l-2.814-2.814a.6.6 0 0 1 0-.846l2.813-2.813c.225-.225.35-.529.35-.846V5.098a.6.6 0 0 0-.597-.598");
}

</style>
