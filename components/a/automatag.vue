<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ab1-szb3l"/><path class="sjtwdcwbs"/><path class="lh6d3obip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:automatag" /></template>
<style>
.ab1-szb3l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 6.577h-9.769v25.035");
}

.lh6d3obip {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.001 41.268a9.811 9.811 0 1 1 7.897-7.793m-16.57-8.801L4.5 8.846");
}

.sjtwdcwbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.73 31.612a6.465 6.465 0 0 1-6.464 6.465h0a6.465 6.465 0 0 1-6.466-6.465h0a6.465 6.465 0 0 1 6.465-6.465h0a6.465 6.465 0 0 1 6.466 6.465Z");
}

</style>
