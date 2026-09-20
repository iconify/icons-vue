<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="k5kf0mv0k"/><ellipse class="j3hlndf9k"/><circle class="c-e2uvbeq"/><path class="ugxrwx7uu"/><path class="ruz5iqupc"/><path class="u0jumjn3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dslrdashboard" /></template>
<style>
.c-e2uvbeq {
  cx: 15.95px;
  cy: 18.18px;
  r: 0.8px;
  fill: currentColor;
}

.j3hlndf9k {
  cx: 27.95px;
  cy: 26.78px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 8.9px;
  ry: 8.7px;
}

.k5kf0mv0k {
  cx: 27.95px;
  cy: 26.78px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5px;
  ry: 4.9px;
}

.ruz5iqupc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.45 13.28c.2-.7.1-2.1 1.5-2.4a25.3 25.3 0 0 1 9.5 0c1.2.2 1.4 2.1 1.9 3l2.2 2.5l4 1.1a1.09 1.09 0 0 1 .8.8l.8 5a23 23 0 0 1 .4 4.5v7.6c0 1.4-1.8 2.1-2.7 2.1H7.15c-1.6 0-1.7-1-1.7-2.4v-15.7L7 17.48l1.9-.1l1.8-1.2h8.6l1.8-2.2");
}

.u0jumjn3j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.25 22.28c1.4-1.3 5.5-2.1 5.6 0v15.3");
}

.ugxrwx7uu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.65 25.08h3.4a2.19 2.19 0 0 1 0 3.3h-3.4m-14.5-15.3h10.9a1.11 1.11 0 0 1 1.1 1.1a1.11 1.11 0 0 1-1.1 1.1h-10.9a1.11 1.11 0 0 1-1.1-1.1a1 1 0 0 1 1.1-1.1m-4.1 3.1v-1.6h-5.8v1.6");
}

</style>
