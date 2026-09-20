<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="eqmavjbvl"/><path class="lsl35gbld"/><rect class="uhx3m_1tm"/><path class="f7gg3pbiy"/><path class="rd78vlb2j"/><path class="ir56vxcru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:creature-journal" /></template>
<style>
.eqmavjbvl {
  cx: 24px;
  cy: 30.565px;
  r: 0.75px;
  fill: currentColor;
}

.f7gg3pbiy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33 37c0 .555-.45 1.005-1.005 1.005c-.617 0-.804-.324-.995-.502S30.622 37 30.005 37C29.45 37 29 37.45 29 38.005M26 37c0 .555-.45 1.005-1.005 1.005c-.617 0-.804-.324-.995-.502S23.622 37 23.005 37C22.45 37 22 37.45 22 38.005M19 37c0 .555-.45 1.005-1.005 1.005c-.617 0-.804-.324-.995-.502S16.622 37 16.005 37C15.45 37 15 37.45 15 38.005M11.1 8.5h9v9h-9z");
}

.ir56vxcru {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.567 9.733c.554-.462 1.15-.672 2.49-.669l.31.002a2 2 0 1 1 0 3.999m-1.536 0h1.537");
}

.lsl35gbld {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.908 22.414c0-.854.346-1.627.906-2.187a3.092 3.092 0 0 1 5.278 2.186c0 .854-.288 1.692-.906 2.187c-.64.513-2.197 1.354-2.197 2.662");
}

.rd78vlb2j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.702 11.102h3.797v3.797h-3.797zm15.163 3.225v.032a2.65 2.65 0 1 1-5.3 0v-2.7a2.65 2.65 0 1 1 5.3 0v.033m2.703 4.698c.552.462 1.149.674 2.488.674h.312a2 2 0 1 0 0-3.999");
}

.uhx3m_1tm {
  width: 31px;
  height: 39px;
  x: 8.5px;
  y: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
