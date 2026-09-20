<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jqu44zbfw"/><path class="vov1pibmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:concentration-training" /></template>
<style>
.jqu44zbfw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.527 17.635c0 5.828-4.707 10.552-10.513 10.552c-5.807 0-10.514-4.725-10.514-10.552c0-5.828 4.707-10.552 10.514-10.552s10.513 4.724 10.513 10.552");
}

.vov1pibmd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 24.096c0 9.29-7.504 16.821-16.76 16.821S9.98 33.386 9.98 24.095c0-9.29 7.503-16.821 16.76-16.821c9.256 0 16.76 7.531 16.76 16.821");
}

</style>
