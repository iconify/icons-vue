<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u492_-bbk"/><path class="i9clfwm2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:5g-only" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.u492_-bbk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.5 29.769c.958.803 1.888 1.17 4.211 1.17h.4A3.89 3.89 0 0 0 22 27.05h0a3.89 3.89 0 0 0-3.89-3.891H13.5V17.06H22m12.5 4.598a4.6 4.6 0 0 0-4.598-4.598h0a4.6 4.6 0 0 0-4.597 4.598v4.684a4.6 4.6 0 0 0 4.597 4.598h0a4.6 4.6 0 0 0 4.598-4.598h-4.598");
}

</style>
