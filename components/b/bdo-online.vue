<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="dffirxsoq"/><rect class="c7bakqbde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bdo-online" /></template>
<style>
.c7bakqbde {
  width: 6.008px;
  height: 9.069px;
  x: 29.492px;
  y: 19.465px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.004px;
  ry: 3.004px;
}

.dffirxsoq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.024 28.535v-9.07h2.04a3.97 3.97 0 0 1 3.968 3.968v1.134a3.97 3.97 0 0 1-3.968 3.968zM16.241 24a2.267 2.267 0 1 1 0 4.535H12.5v-9.07h3.741a2.267 2.267 0 1 1 0 4.535m0 0H12.5");
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

</style>
