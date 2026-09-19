<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><rect class="tioc7mbwb"/><path class="bjl2cvbri"/><rect class="dfhoazn7a"/><path class="hoy619rux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bonbon" /></template>
<style>
.bjl2cvbri {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.343 21.812v-4.46a2.703 2.703 0 0 1 2.703-2.703h0a2.703 2.703 0 0 1 2.703 2.703v4.46m-21.498-4.46a2.703 2.703 0 0 1 2.703-2.703h0a2.703 2.703 0 0 1 2.703 2.703v1.757a2.703 2.703 0 0 1-2.703 2.703h0a2.703 2.703 0 0 1-2.703-2.703m0 0V11");
}

.dfhoazn7a {
  width: 5.406px;
  height: 7.163px;
  x: 21.308px;
  y: 27.837px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.703px;
  ry: 2.703px;
}

.hoy619rux {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.343 35v-4.46a2.703 2.703 0 0 1 2.703-2.703h0a2.703 2.703 0 0 1 2.703 2.703V35m-21.498-4.46a2.703 2.703 0 0 1 2.703-2.703h0a2.703 2.703 0 0 1 2.703 2.703v1.757A2.703 2.703 0 0 1 15.955 35h0a2.703 2.703 0 0 1-2.703-2.703m-.001 0v-8.109");
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.tioc7mbwb {
  width: 5.406px;
  height: 7.163px;
  x: 21.308px;
  y: 14.649px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.703px;
  ry: 2.703px;
}

</style>
