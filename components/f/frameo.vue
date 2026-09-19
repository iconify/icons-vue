<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x6e4cut2x"/><path class="sh_-i8bmi"/><path class="e6100qe0e"/><path class="p4gl1qq8y"/><path class="pbs3euvyw"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:frameo" /></template>
<style>
.e6100qe0e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.791 5.632c-2.791 1.415-1.164 3.5-1.164 3.5M5.5 31.244a20.7 20.7 0 0 0 2.295-2.64a7.2 7.2 0 0 0 1.225-2.852c.16-1.284-.124-3.883 2.524-4.516a3.18 3.18 0 0 1 3.66 1.95a10.2 10.2 0 0 1 .23 4.015a11.4 11.4 0 0 1-.612 3.798s11.382-1.231 15.183-1.57c1.012-.09 3.406-.253 3.612 2.46s-1.941 3.07-2.952 3.2c-3.375.435-13.26 1.58-13.26 1.58");
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

.p4gl1qq8y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.636 39.592s4.593-.59 6.275-.772c1.35-.146 2.164-.623 2.248-1.548a1.93 1.93 0 0 0-.637-1.556");
}

.pbs3euvyw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.209 42.5c2.791-1.415 1.164-3.501 1.164-3.501");
}

.sh_-i8bmi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.365 8.54s-4.594.59-6.276.772c-1.35.146-2.164.623-2.248 1.548a1.93 1.93 0 0 0 .637 1.555");
}

.x6e4cut2x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 16.888a20.7 20.7 0 0 0-2.295 2.64a7.2 7.2 0 0 0-1.225 2.852c-.16 1.283.124 3.883-2.524 4.515a3.18 3.18 0 0 1-3.66-1.95a10.2 10.2 0 0 1-.23-4.014a11.4 11.4 0 0 1 .612-3.798s-11.382 1.231-15.183 1.57c-1.012.09-3.406.253-3.612-2.46s1.941-3.07 2.952-3.2c3.375-.435 13.26-1.58 13.26-1.58");
}

</style>
