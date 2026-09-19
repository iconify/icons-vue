<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="z2yeaublg"/><rect class="g0lc5mcum"/><rect class="u2rld8b-k"/><rect class="y5tpoxbjj"/><rect class="r6d7f0b9y"/><ellipse class="k457aebca"/><circle class="xgwrxmbkt"/><circle class="j1wnwwn_b"/><circle class="czjyknpgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:brick-blast" /></template>
<style>
.czjyknpgx {
  cx: 28.332px;
  cy: 30.716px;
  r: 0.75px;
  fill: currentColor;
}

.g0lc5mcum {
  width: 11.386px;
  height: 8.351px;
  x: 19.116px;
  y: 5.862px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.628px;
  ry: 0.628px;
}

.j1wnwwn_b {
  cx: 23.689px;
  cy: 34.43px;
  r: 0.75px;
  fill: currentColor;
}

.k457aebca {
  cx: 13.089px;
  cy: 38.416px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.797px;
  ry: 3.722px;
}

.r6d7f0b9y {
  width: 9.867px;
  height: 8.351px;
  x: 32.633px;
  y: 5.862px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.628px;
  ry: 0.628px;
}

.u2rld8b-k {
  width: 11.386px;
  height: 8.351px;
  x: 5.5px;
  y: 18.02px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.628px;
  ry: 0.628px;
}

.xgwrxmbkt {
  cx: 19.157px;
  cy: 38.32px;
  r: 0.75px;
  fill: currentColor;
}

.y5tpoxbjj {
  width: 11.386px;
  height: 8.351px;
  x: 19.116px;
  y: 18.02px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.628px;
  ry: 0.628px;
}

.z2yeaublg {
  width: 11.386px;
  height: 8.351px;
  x: 5.5px;
  y: 5.862px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.628px;
  ry: 0.628px;
}

</style>
