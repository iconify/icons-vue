<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k935qm1cz"/><rect class="q41la52gt"/><rect class="zszy5o2gd"/><rect class="c-_ficcvd"/><rect class="o267-64ub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kexp" /></template>
<style>
.c-_ficcvd {
  width: 4.967px;
  height: 21.062px;
  x: 34.187px;
  y: 9.954px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.552px;
  ry: 0.552px;
}

.k935qm1cz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.426 43.5v-8.83h2.89c1.635 0 2.96 1.328 2.96 2.966s-1.325 2.965-2.96 2.965h-2.89m-9.08-5.931l5.85 8.83m0-8.83l-5.85 8.83M16.7 39.085h2.88m1.535 4.415h-4.414v-8.83h4.414m-12.391 0v8.83m0-3.075L13.47 34.7m0 8.8l-3.635-4.415");
}

.o267-64ub {
  width: 4.967px;
  height: 26.516px;
  x: 25.713px;
  y: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.552px;
  ry: 0.552px;
}

.q41la52gt {
  width: 4.967px;
  height: 23.544px;
  x: 8.767px;
  y: 7.471px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.552px;
  ry: 0.552px;
}

.zszy5o2gd {
  width: 4.967px;
  height: 16.897px;
  x: 17.24px;
  y: 14.118px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.552px;
  ry: 0.552px;
}

</style>
