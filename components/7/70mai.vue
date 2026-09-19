<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><circle class="qmxq30bqm"/><path class="fum7tq7dr"/><ellipse class="wggi8kb5k"/><circle class="t9i5p1bmg"/><path class="atj47eb-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:70mai" /></template>
<style>
.atj47eb-v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.51 30.741c1.035-.304 1.63-.48 2.676-.4m5.553-.225q1.689-.164 2.977.375M25.61 5.5c-.212 13.752-7.796 19.735-20.11 19.97");
}

.fum7tq7dr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.922 42.5c.177-1.877-1.102-4.745-2.624-5.563c-.07-2.212-.554-3.95-1.956-5.295c1.374-.608.823-2.316 0-3.277c-1.742-2.036-3.313-.761-3.702 0c-2.906-.933-5.705-1.9-11.205-.1c-.865-1.324-2.348-1.186-3.198-.507c-1.806 1.442-1.595 2.774-.348 3.883c-.83.802-2.076 2.515-2.558 5.078c-1.555 1.058-2.045 2.9-2.05 5.78");
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

.qmxq30bqm {
  cx: 20.375px;
  cy: 33.392px;
  r: 1.25px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.t9i5p1bmg {
  cx: 27.764px;
  cy: 33.392px;
  r: 1.25px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.wggi8kb5k {
  cx: 24px;
  cy: 37.632px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.814px;
  ry: 1.863px;
}

</style>
