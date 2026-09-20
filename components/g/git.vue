<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xnf7gybpw"/><circle class="whj6qs4po"/><circle class="eq2rvcgvj"/><circle class="qatzp8mtw"/><path class="j07-8_bry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:git" /></template>
<style>
.eq2rvcgvj {
  cx: 24px;
  cy: 15.52px;
  r: 3.3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.j07-8_bry {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 29.11V18.82");
}

.qatzp8mtw {
  cx: 32.48px;
  cy: 24px;
  r: 3.3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.whj6qs4po {
  cx: 24px;
  cy: 32.41px;
  r: 3.3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xnf7gybpw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.21 22.12a2.87 2.87 0 0 0 0 3.77L22.12 43.8a2.87 2.87 0 0 0 3.77 0l17.9-17.91a2.85 2.85 0 0 0 0-3.77L25.89 4.21a2.68 2.68 0 0 0-1.89-.7a2.66 2.66 0 0 0-1.88.71Zm22.12-4.27l3.82 3.82M17.4 8.92l4.27 4.27");
}

</style>
