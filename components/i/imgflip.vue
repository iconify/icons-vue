<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c2xrbabwq"/><path class="snmh6gbna"/><ellipse class="q6slks63s"/><path class="v4v7xwbob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:imgflip" /></template>
<style>
.c2xrbabwq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 19.6v18.9a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4h-29a4 4 0 0 0-4 4z");
}

.q6slks63s {
  cx: 11.814px;
  cy: 15.472px;
  fill: currentColor;
  rx: 0.755px;
  ry: 0.75px;
}

.snmh6gbna {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.12 24.216c0-3.154 2.572-5.711 5.746-5.711s5.748 2.557 5.748 5.71v9.138M15.119 18.505v14.848m11.495-9.137c0-3.154 2.573-5.711 5.747-5.711s5.747 2.557 5.747 5.71v9.138");
}

.v4v7xwbob {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.814 18.505v14.848");
}

</style>
