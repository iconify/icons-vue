<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="g8h9vrb6q"/><path class="sgfndbfne"/><rect class="g8x3sjb5q"/><rect class="je3_u1b_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:games" /></template>
<style>
.g8h9vrb6q {
  width: 39px;
  height: 20px;
  x: 4.5px;
  y: 14px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 10px;
}

.g8x3sjb5q {
  width: 4.82px;
  height: 4.82px;
  x: 27.79px;
  y: 24.23px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.41px;
}

.je3_u1b_p {
  width: 4.82px;
  height: 4.82px;
  x: 33.07px;
  y: 18.95px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.41px;
}

.sgfndbfne {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.66 22.43h-1.29v-1.29a1.57 1.57 0 1 0-3.14 0v1.29h-1.29a1.57 1.57 0 1 0 0 3.14h1.29v1.29a1.57 1.57 0 0 0 3.14 0v-1.29h1.29a1.57 1.57 0 0 0 0-3.14");
}

</style>
