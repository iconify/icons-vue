<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kg4ghsblu"/><g class="y9tr6bcfx"><path class="n__dzqb7c"/><path class="e1g0dvwzr"/><circle class="s23uhwbbm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:app-lock" /></template>
<style>
.e1g0dvwzr {
  d: path("M19.726 21.048v-1.79a4.27 4.27 0 0 1 8.541 0v1.79");
}

.kg4ghsblu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 43.5c9.043-3.117 15.489-10.363 16.5-19.589c.28-4.005.257-8.025-.071-12.027a2.54 2.54 0 0 0-2.468-2.366c-4.091-.126-8.846-.808-12.52-4.427a2.05 2.05 0 0 0-2.881 0c-3.675 3.619-8.43 4.301-12.52 4.427a2.54 2.54 0 0 0-2.468 2.366A79.4 79.4 0 0 0 7.5 23.911C8.512 33.137 14.957 40.383 24 43.5");
}

.n__dzqb7c {
  d: path("M18.322 21.048h11.356c.43 0 .78.349.78.78v8.392c0 .43-.35.78-.78.78H18.322a.78.78 0 0 1-.78-.78v-8.393c0-.43.35-.78.78-.78");
}

.s23uhwbbm {
  cx: 23.996px;
  cy: 26.024px;
  r: 1.656px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
