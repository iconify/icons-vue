<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y6b6ges9g"/><path class="z7leotb4c"/><path class="x4jheabbp"/><path class="mgo4pxb4d"/><path class="ns-qmvynp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:freeblocks" /></template>
<style>
.mgo4pxb4d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.167 17.833h6.167V24h-6.167zm0 18.501v6.167H24v-6.167zm12.334-.001V42.5h-6.167v-6.167zm-.001-6.167v6.167h-6.167v-6.167zM30.166 24v6.167h-6.167V24z");
}

.ns-qmvynp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.001 36.333V42.5h-6.167v-6.167zm-6.167.001v6.167h-6.167v-6.167zm-6.167 0v6.167H5.5v-6.167zm6.166-6.167v6.167h-6.167v-6.167zm0-18.5H24v6.167h-6.167z");
}

.x4jheabbp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.667 17.833h6.167V24h-6.167zm18.5-6.166h6.167v6.167h-6.167z");
}

.y6b6ges9g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 11.667h6.167v6.167H5.5zm0-6.167h6.167v6.167H5.5zm18.5 0h6.167v6.167H24zm6.167 0h6.167v6.167h-6.167z");
}

.z7leotb4c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.333 5.5H42.5v6.167h-6.167zm-24.666 6.167h6.167v6.167h-6.167z");
}

</style>
