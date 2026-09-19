<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><rect class="cx2bfibcy"/><path class="yvsalintd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:linkbox" /></template>
<style>
.cx2bfibcy {
  width: 24.295px;
  height: 15.857px;
  x: 11.835px;
  y: 16.087px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 7.928px;
  ry: 7.928px;
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.yvsalintd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.894 22.206h4.173c.977 0 1.77.792 1.77 1.77h0a1.77 1.77 0 0 1-1.77 1.768h-4.173a1.77 1.77 0 0 1-1.769-1.769h0a1.77 1.77 0 0 1 1.77-1.769");
}

</style>
