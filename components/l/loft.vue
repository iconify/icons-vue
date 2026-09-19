<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="aa5u97boi"/><path class="fx8fplq3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:loft" /></template>
<style>
.aa5u97boi {
  cx: 15.677px;
  cy: 24.84px;
  r: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.fx8fplq3k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 12.5v23h11.177m22.234-23v23H43.5m0-13.675h-8.383M24.853 35.5v-23h5.589m-.001 9.325h-5.589");
}

</style>
