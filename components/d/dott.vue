<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j4baqpkhr"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dott" /></template>
<style>
.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.j4baqpkhr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.466 18.575V27.5a1.5 1.5 0 0 0 1.5 1.5h.45m-1.95-7.95h1.95m2.713-2.475V27.5a1.5 1.5 0 0 0 1.5 1.5h.45m-1.95-7.95h1.95m-18.158 3a3 3 0 0 0-3-3h0a3 3 0 0 0-3 3V26a3 3 0 0 0 3 3h0a3 3 0 0 0 3-3m0 0v-9m2.777 7.05a3 3 0 1 1 6 0V26a3 3 0 1 1-6 0z");
}

</style>
