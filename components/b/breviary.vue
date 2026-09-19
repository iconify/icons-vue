<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uhno83b8l"/><path class="pz1xg0bcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:breviary" /></template>
<style>
.pz1xg0bcs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.63 45.05L26 28.19l10.54 4l2.37-6.29l-10.55-4l3.9-10.36l-6.3-2.37L22 19.53l-10.54-4l-2.33 6.33l10.54 4l-6.33 16.82");
}

.uhno83b8l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.34 42.68a21.48 21.48 0 1 1 6.29 2.37");
}

</style>
