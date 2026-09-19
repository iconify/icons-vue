<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="djd3sp3dr"/><path class="pbtsm4q9j"/><circle class="zmixk65dh"/><path class="jiikjhyig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:duck-life-2" /></template>
<style>
.djd3sp3dr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.927 42.426q-.602-6.815 4.41-11.911L7.468 13.63l14.03-8.13l9.562 11.051q4.151 2.578 5.554 7.444q1.338 4.64-2.004 9.449q2.806 4.47 2.061 9.056M8.351 29.097l26.397-15.232");
}

.jiikjhyig {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.472 20.582c-2.827 1.672-2.818 3.61.046 5.949");
}

.pbtsm4q9j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m36.82 24.839l3.711 1.856l-3.684 1.653");
}

.zmixk65dh {
  cx: 29.262px;
  cy: 23.573px;
  r: 3.719px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
