<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="gqqk3rb7u"/><path class="bmedoqb9s"/><circle class="nuv9dtbnd"/><circle class="oow4e4xlt"/><path class="rr_72hsof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fatebook" /></template>
<style>
.bmedoqb9s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.167 4.5v39M31.583 5.042v8.125m4.334-8.125v8.125m-4.334 0L33.75 11l2.167 2.167");
}

.gqqk3rb7u {
  width: 30.333px;
  height: 39px;
  x: 8.833px;
  y: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.nuv9dtbnd {
  cx: 21.833px;
  cy: 19.667px;
  r: 2.167px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.oow4e4xlt {
  cx: 28.333px;
  cy: 28.333px;
  r: 2.167px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.rr_72hsof {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.5 17.5l-10.833 13");
}

</style>
