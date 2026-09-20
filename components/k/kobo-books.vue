<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><rect class="cuzsle0dq"/><rect class="m45nyfbrf"/><path class="uxuk6nbvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kobo-books" /></template>
<style>
.cuzsle0dq {
  width: 5.435px;
  height: 7.202px;
  x: 33.065px;
  y: 20.341px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.717px;
  ry: 2.717px;
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.m45nyfbrf {
  width: 5.435px;
  height: 7.202px;
  x: 16.922px;
  y: 20.341px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.717px;
  ry: 2.717px;
}

.uxuk6nbvq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 16.673v10.87m.001-2.309l4.92-4.897m-3.354 3.338l3.868 3.851m10.015-4.467a2.717 2.717 0 1 1 5.435 0v1.766a2.717 2.717 0 1 1-5.435 0m0 2.718v-10.87");
}

</style>
