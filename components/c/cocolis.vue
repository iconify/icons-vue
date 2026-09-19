<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w4wdlhbhh"/><path class="trppb0b-w"/><path class="nugs0bc7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cocolis" /></template>
<style>
.nugs0bc7h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.255 13.68L23.801 3.5l17.944 10.18v20.632L23.995 44.5L6.256 34.312z");
}

.trppb0b-w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.8 29.934a8.42 8.42 0 1 1-6.172-14.15");
}

.w4wdlhbhh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.417 15.918c4.616 0 8.356 3.74 8.356 8.347a8.357 8.357 0 0 1-8.357 8.357h0a8.353 8.353 0 0 1 0-16.705");
}

</style>
