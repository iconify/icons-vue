<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="ol6aijb1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:1alv" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.ol6aijb1d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m16.063 18.542l3.75-2.042v15m12.124-3.75a3.75 3.75 0 0 1-3.75 3.75h0a3.75 3.75 0 0 1-3.75-3.75v-2.437a3.75 3.75 0 0 1 3.75-3.75h0a3.75 3.75 0 0 1 3.75 3.75m0 6.187v-9.937");
}

</style>
