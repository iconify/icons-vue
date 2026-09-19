<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zoi7e1brx"/><g class="y9tr6bcfx"><ellipse class="tk06c6w8a"/><ellipse class="o95551eba"/><ellipse class="an1z1obtc"/><ellipse class="y2o2oiuwi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:brace" /></template>
<style>
.an1z1obtc {
  cx: 27.287px;
  cy: 29.944px;
  rx: 3.644px;
  ry: 3.639px;
}

.o95551eba {
  cx: 27.287px;
  cy: 19.712px;
  rx: 3.644px;
  ry: 3.639px;
}

.tk06c6w8a {
  cx: 17.132px;
  cy: 19.712px;
  rx: 3.644px;
  ry: 3.639px;
}

.y2o2oiuwi {
  cx: 17.132px;
  cy: 29.944px;
  rx: 3.644px;
  ry: 3.639px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zoi7e1brx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.881 8.55v30.76c0 1.978 1.101 3.19 3.303 3.19h20.191c7.474 0 13.589-15.873 3.28-20.357c7.592-4.376 4.99-16.631-2.431-16.631c-5.067 0-21.528-.012-21.528-.012c-2.046 0-2.815.968-2.815 3.05");
}

</style>
