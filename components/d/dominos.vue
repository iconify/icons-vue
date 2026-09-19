<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect transform="rotate(45 23.999 24)" class="l7ydgvuzd"/><path class="j0lda3b3b"/><circle class="nbsql2b4j"/><circle class="gwh775brf"/><circle class="nazuiob6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dominos" /></template>
<style>
.gwh775brf {
  cx: 21.85px;
  cy: 30.51px;
  r: 2.98px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.j0lda3b3b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.82 17.82l12.36 12.36");
}

.l7ydgvuzd {
  width: 17.47px;
  height: 35.91px;
  x: 15.27px;
  y: 6.04px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.9px;
}

.nazuiob6c {
  cx: 13.12px;
  cy: 30.51px;
  r: 2.98px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.nbsql2b4j {
  cx: 30.55px;
  cy: 17.45px;
  r: 2.98px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
