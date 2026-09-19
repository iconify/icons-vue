<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g1_a_bb8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:google-camera" /></template>
<style>
.g1_a_bb8n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.6 9.54v2.11H6.29a1.79 1.79 0 0 0-1.79 1.79h0v23.23a1.79 1.79 0 0 0 1.79 1.79h35.42a1.79 1.79 0 0 0 1.79-1.79h0V13.45a1.8 1.8 0 0 0-1.79-1.8H16.39V9.54ZM24 17.75a8.52 8.52 0 1 1-8.51 8.51A8.51 8.51 0 0 1 24 17.75");
}

</style>
