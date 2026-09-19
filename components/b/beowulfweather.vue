<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f5rxsl-aa"/><path class="q81klcbez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:beowulfweather" /></template>
<style>
.f5rxsl-aa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.149 23.716C10.71 12.371 25.12 11.311 26.724 21.688c3.489-2.662 7.874.279 7.05 4.917c8.227.074 7.03 9.678 2.226 9.925H10.026c-7.018.174-8.418-12.394 2.123-12.814l-.267-.173");
}

.q81klcbez {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.1 16.008a10.668 10.668 0 1 1 15.636 14.26");
}

</style>
