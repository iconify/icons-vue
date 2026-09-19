<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xw17p2jsg"/><path class="kzykk8swa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calendar-samsung-28" /></template>
<style>
.kzykk8swa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-4v1a3.5 3.5 0 1 1-7 0v-1h-8v1a3.5 3.5 0 1 1-7 0v-1h-3a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.xw17p2jsg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.662 25.333c0-2.963 2.37-5.333 5.136-5.333s5.334 2.37 5.334 5.333c0 1.383-.593 2.766-1.58 3.753c-2.174 1.778-8.89 6.914-8.89 6.914h10.47m10.373-8h-2.6c-2.2 0-4 1.8-4 4h0c0 2.2 1.8 4 4 4h2.6c2.2 0 4-1.8 4-4h0c0-2.2-1.8-4-4-4m0 0c2.2 0 4-1.8 4-4h0c0-2.2-1.8-4-4-4h-2.6c-2.2 0-4 1.8-4 4h0c0 2.2 1.8 4 4 4");
}

</style>
