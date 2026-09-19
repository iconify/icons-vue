<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hjsq5-bmv"/><path class="ybm6tc1eu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:geometry-dash-alt" /></template>
<style>
.hjsq5-bmv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M3.5 24L24 3.5L44.498 24l-20.5 20.5z");
}

.ybm6tc1eu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m11.635 24.823l3.879-3.878l3.878 3.878l-3.878 3.878zm8.965-8.965l3.879-3.879l3.878 3.879l-3.878 3.878zm-1.252 17.687L33.2 19.693l3.324 3.324L22.673 36.87z");
}

</style>
