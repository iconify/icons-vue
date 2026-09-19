<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="ybx38oxac"/><path class="x99gs5e7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:americanas" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.x99gs5e7x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.484 19.02c1.13-1.132 1.922-1.231 4.102-1.231c2.475 0 4.102 1.089 4.102 4.032v8.39M16.733 13.5h14.534m-14.534 21h14.534");
}

.ybx38oxac {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.679 25.524c0 2.588-2.083 4.687-4.652 4.687h-1.633c-1.702 0-3.082-1.39-3.082-3.105S20.692 24 22.394 24h6.294");
}

</style>
