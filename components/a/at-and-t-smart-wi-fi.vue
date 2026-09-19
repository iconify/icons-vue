<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ss0pnnb3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:at-and-t-smart-wi-fi" /></template>
<style>
.ss0pnnb3b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.163 31.663c-5.62-5.62-6.012-14.601-.904-20.688m23.481 0c5.108 6.087 4.716 15.069-.903 20.688M14.149 9.086a15.326 15.326 0 0 1 19.702 0m-16.525 3.787a10.38 10.38 0 0 1 13.348 0m-10.17 3.787a5.44 5.44 0 0 1 6.992 0m7.341 15.003L24 42.5L13.163 31.663");
}

</style>
