<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uh32bd67f"/><circle class="cvjf-z6la"/><circle class="stmccvbdk"/><path class="adizzobpn"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:coffee-golf" /></template>
<style>
.adizzobpn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m19.111 18.866l6.645-2.054l-6.645-2.452m6.719 14.181c.756-9.717 6.995-17.895 15.623-21.445M16.746 32.528h14.916c1.656 0 3 1.344 3 3V42.5H13.746v-6.972c0-1.656 1.344-3 3-3");
}

.cvjf-z6la {
  cx: 25.668px;
  cy: 30.53px;
  r: 1.998px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.stmccvbdk {
  cx: 19.111px;
  cy: 13.456px;
  r: 0.904px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.uh32bd67f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.111 14.36v18.168");
}

</style>
