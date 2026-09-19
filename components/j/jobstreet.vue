<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="o9s4sebes"/><rect class="toh6o6bdc"/><path class="utvam1b2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:jobstreet" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.o9s4sebes {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.912 18.088v7.368c0 1.356-1.1 2.456-2.456 2.456h0A2.456 2.456 0 0 1 11 25.456v-.816");
}

.toh6o6bdc {
  width: 4.912px;
  height: 6.508px;
  x: 18.299px;
  y: 21.404px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.456px;
  ry: 2.456px;
}

.utvam1b2y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.806 27.363c.448.377.932.549 2.02.549h.55c.897 0 1.624-.728 1.624-1.627h0c0-.899-.727-1.627-1.624-1.627h-1.102a1.625 1.625 0 0 1-1.623-1.627h0c0-.899.727-1.627 1.623-1.627h.551c1.088 0 1.572.172 2.02.549M25.541 23.86c0-1.357 1.1-2.456 2.456-2.456h0c1.356 0 2.456 1.1 2.456 2.456v1.596c0 1.356-1.1 2.456-2.456 2.456h0a2.456 2.456 0 0 1-2.456-2.456m0 2.456v-9.824");
}

</style>
