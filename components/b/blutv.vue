<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="z6u8k0bha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:blutv" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.z6u8k0bha {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.964 19.3v7.004a2.395 2.395 0 0 0 2.395 2.395M9.05 19.3v6.327m6.145 0a3.07 3.07 0 0 1-3.072 3.072h0a3.07 3.07 0 0 1-3.073-3.072h0a3.07 3.07 0 0 1 3.072-3.072h0a3.07 3.07 0 0 1 3.073 3.072m6.772-4.201v4.666a2.607 2.607 0 0 0 2.607 2.607h0a2.607 2.607 0 0 0 2.606-2.607q0 0 0 0v-4.654m11.77.597l-2.711 6.664l-2.711-6.664h-4.18m1.49-2.735v8.249c0 .635.514 1.15 1.15 1.15h0");
}

</style>
