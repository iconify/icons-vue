<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nvl_-8dyp"/><circle class="jbfqe4sfl"/><circle class="c821lybim"/><path class="j7-uroqyf"/><path class="y7thrnuvs"/><rect class="vnsugxbts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:digital-watch" /></template>
<style>
.c821lybim {
  cx: 23.142px;
  cy: 22.425px;
  r: 0.75px;
  fill: currentColor;
}

.j7-uroqyf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.867 20.12h1.717v3.89H35.87m-.003 1.856h1.717V28.5H35.87");
}

.jbfqe4sfl {
  cx: 23.142px;
  cy: 25.608px;
  r: 0.75px;
  fill: currentColor;
}

.nvl_-8dyp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.814 36.08l-.453 5.656a2.04 2.04 0 0 1-2.024 1.764H17.946a2.04 2.04 0 0 1-2.024-1.763l-.453-5.658M26.556 43.5v-6.757m-6.83 6.757v-6.757m.737-2.945h5.133m-8.469-7.19v-5.183m2.599 5.183v-5.183m6.567 5.183v-5.183m2.526 5.183v-5.183m1.995-9.571l-.453-5.59A2.04 2.04 0 0 0 28.337 4.5H17.946c-1.02 0-1.885.753-2.024 1.764l-.453 5.59M26.556 4.5v6.79m-6.83-6.79v6.79");
}

.vnsugxbts {
  width: 20.665px;
  height: 15.334px;
  x: 12.809px;
  y: 16.349px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.057px;
  ry: 3.057px;
}

.y7thrnuvs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.869 17.677v12.679a2.95 2.95 0 0 1-1.003 2.216l-3.745 3.29a3.54 3.54 0 0 1-2.338.88H17.5c-.86 0-1.691-.312-2.338-.88l-3.744-3.29a2.95 2.95 0 0 1-1.003-2.216v-12.68a2.95 2.95 0 0 1 1.003-2.216l3.744-3.29a3.54 3.54 0 0 1 2.338-.88h11.282c.86 0 1.692.313 2.338.88l3.744 3.29a2.95 2.95 0 0 1 1.004 2.217");
}

</style>
