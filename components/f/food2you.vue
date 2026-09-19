<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="zrufyx0cy"/><rect class="r3nflscua"/><rect class="lryh_z3hb"/><rect class="fs2ff6bbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:food2you" /></template>
<style>
.fs2ff6bbv {
  width: 5.3px;
  height: 8px;
  x: 23.5px;
  y: 15px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.65px;
  ry: 2.65px;
}

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

.lryh_z3hb {
  width: 5.3px;
  height: 8px;
  x: 25px;
  y: 25px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.65px;
  ry: 2.65px;
}

.r3nflscua {
  width: 5.3px;
  height: 8px;
  x: 16.4px;
  y: 15px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.65px;
  ry: 2.65px;
}

.zrufyx0cy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m23.2 25l-2.65 4l-2.65-4m2.65 8v-4m11.55-4v5.35a2.65 2.65 0 1 0 5.3 0V25m-6.8-2v-8h1.8a3.5 3.5 0 0 1 3.5 3.5v1a3.5 3.5 0 0 1-3.5 3.5zm-20-4h2.6m-2.6 4v-8h4m-4 12.65a2.653 2.653 0 0 1 3.176-2.6c1.111.214 1.999 1.175 2.11 2.302c.082.837-.184 1.664-.762 2.172C14.052 30.464 10.6 33 10.6 33h5.3");
}

</style>
