<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="o9xb5gslp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:camobile" /></template>
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

.o9xb5gslp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.493 26.256v.056a4.496 4.496 0 0 1-4.497 4.496h0a4.496 4.496 0 0 1-4.496-4.496V21.73a4.496 4.496 0 0 1 4.496-4.496h0a4.496 4.496 0 0 1 4.497 4.496v.056m8.421 4.213h-5.902m-1.593 4.855l4.54-13.708L33.5 30.854");
}

</style>
