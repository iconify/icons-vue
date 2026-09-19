<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="g9ewtzbbj"/><path class="b75-zvbbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:getir" /></template>
<style>
.b75-zvbbb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.508 16.925c0-1.822-.779-7.066-6.751-7.066c-3.592 0-7.542 3.477-7.542 9.674c0 4.15 2.664 6.616 6.14 6.616c3.617 0 8.153-3.056 8.153-9.224");
}

.g9ewtzbbj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.271 42.5c-2.635-1.621-3.42-6.397-.841-9.257c4.206 5.215 10.935 6.393 13.402 6.393s5.221-1.049 6.224-4.879c.668-2.553 1.178-4.598 1.178-4.598c-4.935 3.14-8.355 3.71-13.29.762s-9.196-11.809-3.42-21.23A22.7 22.7 0 0 1 21.8 5.5");
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

</style>
