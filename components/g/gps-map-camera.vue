<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u8mmfccym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gps-map-camera" /></template>
<style>
.u8mmfccym {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 4.5c-8.185 0-14.82 6.635-14.82 14.82h0v1.08c.6 8.12 7.34 14.65 14.82 23.1c7.81-8.82 14.82-15.5 14.82-24.18h0C38.82 11.135 32.185 4.5 24 4.5m10 14.83c0 5.523-4.477 10-10 10s-10-4.477-10-10s4.477-10 10-10s10 4.477 10 10m-4.05-3.906a2.044 2.044 0 1 1-4.089 0a2.044 2.044 0 0 1 4.09 0");
}

</style>
