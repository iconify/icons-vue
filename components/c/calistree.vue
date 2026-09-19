<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="kn3v_bj-u"/><circle class="h7_r23o4y"/><circle class="ss2rf3fnw"/><path class="tc4wk_bzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calistree" /></template>
<style>
.h7_r23o4y {
  cx: 13px;
  cy: 20px;
  r: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.kn3v_bj-u {
  cx: 24px;
  cy: 38px;
  r: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ss2rf3fnw {
  cx: 35.5px;
  cy: 8.5px;
  r: 4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.tc4wk_bzt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.5 20c3.544 0 6.5.5 6.5 6.5m7.5-18C25.108 8.5 24 12.916 24 20v12.5");
}

</style>
