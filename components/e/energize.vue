<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="nif55rbip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:energize" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.nif55rbip {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.365 16.033L34.755 9.5c1.197 2.817-.358 5.498-3.207 6.707l-15.39 6.533c-1.196-2.817.382-5.508 3.207-6.707M14.662 26.23l15.39-6.532c1.197 2.817-.358 5.497-3.207 6.707l-15.39 6.532c-1.196-2.816.382-5.507 3.207-6.706m6.49 5.562l15.39-6.533c1.196 2.818-.358 5.498-3.207 6.707L17.945 38.5c-1.196-2.816.381-5.507 3.207-6.707");
}

</style>
