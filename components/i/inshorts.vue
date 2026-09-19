<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="v77m4psds"/><circle class="h397d3j1k"/><circle class="lgn-g1b3f"/><circle class="e_fpvcbmy"/><path class="thkq3tsbr"/><circle class="j7fr-d2wy"/><circle class="kusso3bla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:inshorts" /></template>
<style>
.e_fpvcbmy {
  cx: 38.5px;
  cy: 9.5px;
  r: 4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.h397d3j1k {
  cx: 9.5px;
  cy: 38.5px;
  r: 4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.j7fr-d2wy {
  cx: 38.5px;
  cy: 23.278px;
  r: 4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.kusso3bla {
  cx: 24px;
  cy: 23.278px;
  r: 4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.lgn-g1b3f {
  cx: 24px;
  cy: 38.5px;
  r: 4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.thkq3tsbr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 5.5a4 4 0 0 1 0 8H9.5a4 4 0 0 1 0-8Z");
}

.v77m4psds {
  cx: 38.5px;
  cy: 38.5px;
  r: 4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
