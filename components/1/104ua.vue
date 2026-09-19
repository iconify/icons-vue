<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="me3uygzlb"/><path class="eeh9v1gum"/><path class="eutj9k8lh"/><circle class="aapynsnpz"/><path class="pb0045bed"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:104ua" /></template>
<style>
.aapynsnpz {
  cx: 17.212px;
  cy: 36.968px;
  r: 0.75px;
  fill: currentColor;
}

.eeh9v1gum {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  d: path("M21.236 25.436a4.864 4.864 0 0 1-4.864-4.864v-4.957a4.864 4.864 0 1 1 9.729 0v4.957a4.864 4.864 0 0 1-4.865 4.864Z");
}

.eutj9k8lh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.653 25.436V10.75l-7.882 9.866H38.5");
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

.me3uygzlb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m9.5 12.75l3.672-2v14.687M24.95 12.48l-7.44 11.227");
}

.pb0045bed {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.941 28.436v5.467a3.313 3.313 0 1 0 6.626.001v-5.468m.001 5.467v3.313m10.092-3.313a3.31 3.31 0 0 1-3.312 3.313h-.002a3.31 3.31 0 0 1-3.313-3.311v-2.156a3.31 3.31 0 0 1 3.312-3.313h.002a3.31 3.31 0 0 1 3.313 3.312v.001m0 5.467v-8.78");
}

</style>
