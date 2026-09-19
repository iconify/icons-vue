<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u6evelj2w"/><path class="dg4asablj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:goodweather" /></template>
<style>
.dg4asablj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.45 18.37a6.22 6.22 0 1 0-8.58 8.21m3-14.3V8.75m6.25 6.12l2.5-2.5m-15 15.01l-2.5 2.49m-.09-8.75H4.5m6.12-6.25l-2.5-2.5");
}

.u6evelj2w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.57 17.33a10.14 10.14 0 0 1 8.54 5.46c10.47 1.8 9.21 15.22 0 16.46H16.88a6.88 6.88 0 0 1 .05-13.71c1.54-5.88 6.18-8.45 10.64-8.21m0 0");
}

</style>
