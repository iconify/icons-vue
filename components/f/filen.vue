<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><circle class="jrudqacct"/><circle class="krgcugvqt"/><circle class="il9tqn0ba"/><circle class="cjcrqsbwb"/><path class="pjvaf-ljd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:filen" /></template>
<style>
.cjcrqsbwb {
  cx: 21.869px;
  cy: 29.36px;
  r: 2.131px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.il9tqn0ba {
  cx: 26.857px;
  cy: 9.257px;
  r: 2.131px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.jrudqacct {
  cx: 28.348px;
  cy: 25.356px;
  r: 2.932px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.krgcugvqt {
  cx: 13.749px;
  cy: 24px;
  r: 2.131px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.pjvaf-ljd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.348 28.288v16.628M24.726 9.257H8.356m-2.583 3.337v22.608m7.976-13.333V16.9H34.85V5.436m0 37.127V25.356h10.607M19.738 29.36h-5.989v13.543");
}

</style>
