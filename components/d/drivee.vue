<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="b23oqvbvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:drivee" /></template>
<style>
.b23oqvbvp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 28.571c1.25-.33 2.87-.8 4.55-1.42c-.91-1.98-1.07-4.45-.5-6.48c.69-2.52 2.89-5.66 5.43-5.59c3.37.1 4.01 2.55 3.99 4.58c-.03 3.46-4.67 5.94-8.92 7.49c.38.85.9 1.61 1.57 2.21c2.9 2.6 8.56 2.19 13.78.29c-1.28-1.85-2-4.21-1.72-6.9c.46-4.47 4.57-8.84 8.24-8.53c3.98.34 4.92 3.16 4.77 5.72c-.21 3.65-5.47 7.6-11.29 9.71c1.8 2.64 4.72 4.22 7.42 4.14c3.58-.09 6.86-1.51 9.68-4.04");
}

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

</style>
