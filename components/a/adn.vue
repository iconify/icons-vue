<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="ypcd29noy"/><path class="oloys7n9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:adn" /></template>
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

.oloys7n9u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m10 29.13l3.408-10.26h4.884");
}

.ypcd29noy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.496 29.13V18.87L38 29.13V18.87M21.7 29.13l-3.408-10.26h5.716a4.49 4.49 0 0 1 4.488 4.489v1.282a4.49 4.49 0 0 1-4.488 4.488zm-10.01-5.072h11.989");
}

</style>
