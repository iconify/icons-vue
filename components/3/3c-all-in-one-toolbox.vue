<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ifgdt0b1v"/><path class="am6gowm5g"/><path class="rjryd9bra"/><path class="j80z5slfo"/><path class="aj_ke9b9r"/><circle class="r-2nj0wfa"/><circle class="lue8vzb4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:3c-all-in-one-toolbox" /></template>
<style>
.aj_ke9b9r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.241 24h7.294");
}

.am6gowm5g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 29.075a9.851 9.851 0 1 1-19.693 0v-10.15a9.96 9.96 0 0 1 9.846-10.15c5.47 0 9.482 4.512 9.482 10.15");
}

.ifgdt0b1v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.535 24a7.43 7.43 0 0 0 7.293-7.518a7.43 7.43 0 0 0-7.293-7.518m0 30.073a7.521 7.521 0 0 0 0-15.036M4.5 36.405c2.188 1.88 4.011 2.631 9.117 2.631h2.918M4.5 11.596c2.188-1.88 4.376-2.631 9.117-2.631h2.918");
}

.j80z5slfo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  d: path("m38.694 20.885l1.773-1.772M29.24 20.885l-1.773-1.772");
}

.lue8vzb4f {
  cx: 36.835px;
  cy: 24.451px;
  r: 0.75px;
  fill: currentColor;
}

.r-2nj0wfa {
  cx: 31.111px;
  cy: 24.451px;
  r: 0.75px;
  fill: currentColor;
}

.rjryd9bra {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.364 25.496a6.604 6.604 0 0 1 13.207 0v3.116a.691.691 0 0 1-.679.688H28.06a.692.692 0 0 1-.696-.688Z");
}

</style>
