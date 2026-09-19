<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mdp1vwbfp"/><circle class="es8vy_bnp"/><circle class="uh63l0_7q"/><path class="j98an1bqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calendara" /></template>
<style>
.es8vy_bnp {
  cx: 32.5px;
  cy: 11px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.j98an1bqd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4z");
}

.mdp1vwbfp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.722 29.341c0 3.697-3.025 6.722-6.722 6.722s-6.722-3.025-6.722-6.722v-4.37c0-3.696 3.025-6.72 6.722-6.72s6.722 3.024 6.722 6.72m2.71 11.092c-1.344 0-2.688-1.344-2.688-2.689V18.25");
}

.uh63l0_7q {
  cx: 15.5px;
  cy: 11px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
