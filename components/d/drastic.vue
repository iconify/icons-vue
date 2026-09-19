<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="shs_gib6b"/><rect class="xg4zz7xtx"/><path class="c61_6_6jz"/><path class="um7tebcdj"/><path class="u1xvfsbtd"/><path class="dm59c73mg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:drastic" /></template>
<style>
.c61_6_6jz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.012 25.793H11.418A2.606 2.606 0 0 0 8.9 27.725L5.565 40.173a1.534 1.534 0 0 0 1.482 1.932h16.965");
}

.dm59c73mg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.012 28.683h8.296a1.22 1.22 0 0 1 1.197.98l1.604 7.986a.82.82 0 0 1-.803.98H24.012");
}

.shs_gib6b {
  width: 18.722px;
  height: 11.25px;
  x: 14.651px;
  y: 9.155px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.766px;
}

.u1xvfsbtd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.012 25.793h12.594a2.606 2.606 0 0 1 2.518 1.932l3.335 12.448a1.534 1.534 0 0 1-1.482 1.932H24.012");
}

.um7tebcdj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.012 28.683h-8.296a1.22 1.22 0 0 0-1.197.98l-1.604 7.986a.82.82 0 0 0 .803.98h10.294");
}

.xg4zz7xtx {
  width: 28.515px;
  height: 16.888px;
  x: 9.755px;
  y: 5.918px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.766px;
}

</style>
