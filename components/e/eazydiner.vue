<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yan4e7twr"/><circle class="v2sa847jv"/><path class="s0b_hxisk"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:eazydiner" /></template>
<style>
.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.s0b_hxisk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.093 20.767v6.077m7.062 0v-3.783a2.293 2.293 0 1 0-4.586 0m0 3.783v-6.077m11.354 4.92a2.293 2.293 0 0 1-4.285-1.136v-1.49a2.293 2.293 0 1 1 4.586 0v.745h-4.586m-12.052-.746a2.293 2.293 0 1 0-4.586 0v1.491a2.293 2.293 0 1 0 4.586 0m0 2.293v-9.172");
}

.v2sa847jv {
  cx: 18.093px;
  cy: 17.959px;
  r: 0.803px;
  fill: currentColor;
}

.yan4e7twr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.707 23.06A2.293 2.293 0 0 1 37 20.769m-2.293-.002v6.077");
}

</style>
