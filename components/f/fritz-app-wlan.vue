<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ri7aq9ilb"/><circle class="jzhq8gkwr"/><path class="qug8wob1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fritz-app-wlan" /></template>
<style>
.jzhq8gkwr {
  cx: 39.03px;
  cy: 11.688px;
  r: 0.72px;
  fill: currentColor;
}

.qug8wob1w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.731 34.158a7.71 7.71 0 0 0-9.854-.027v.027m4.908 3.157a3.092 3.092 0 1 0 3.092 3.093v0h0a3.09 3.09 0 0 0-3.092-3.093m9.65-8.504a15.164 15.164 0 0 0-19.3 0M39.071 23.2a22.42 22.42 0 0 0-28.603 0");
}

.ri7aq9ilb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m23.582 13.344l.009-8.232M8.25 13.857V4.5h4.679M8.25 9.179h3.041m3.374 5.848V7.109h2.574a2.672 2.672 0 1 1 0 5.345h-2.574m13.613 2.473V6.83m-2.384-.09h4.768m1.305-1.8h4.769l-4.769 8.098h4.769M19.91 15.027l-2.483-2.582M39.615 5.39l-.45 4.499");
}

</style>
