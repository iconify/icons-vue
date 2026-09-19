<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="orlraabal"/><ellipse class="yx9anwbgu"/><path class="ok_d9_b9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:block-this" /></template>
<style>
.ok_d9_b9r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.25 20.14H43.5v7.083h-3.606v7.343h-7.083v-7.343h-8.525");
}

.orlraabal {
  cx: 14.701px;
  cy: 23.776px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 10.201px;
  ry: 10.342px;
}

.yx9anwbgu {
  cx: 14.701px;
  cy: 23.776px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.55px;
  ry: 2.585px;
}

</style>
