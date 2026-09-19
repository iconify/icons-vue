<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="s8maw6oep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:darty" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.s8maw6oep {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.954 28.653v-9.307h3.01c1.703 0 3.083 1.4 3.083 3.126s-1.38 3.125-3.082 3.125h-3.011m3.011 0l3.012 3.054m1.88-9.305h6.093m-3.047 9.307v-9.307m10.95.001L39.807 24l-3.047-4.653m3.047 9.307V24m-34.66 4.653v-9.307h2.069c2.222 0 4.024 1.823 4.024 4.072v1.163c0 2.249-1.802 4.072-4.024 4.072zm12.987-3.083h-4.075m-1.009 3.083l3.047-9.307l3.046 9.307");
}

</style>
