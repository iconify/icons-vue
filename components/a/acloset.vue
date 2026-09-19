<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vp8w92dlw"/><path class="w57la6bby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:acloset" /></template>
<style>
.vp8w92dlw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.382 27.638c10.876-3.617 23.766-.631 31.118-3.85");
}

.w57la6bby {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 41.831c3.742.341 5.648-.533 7.454-4.645C20.99 18.895 29.8 4.328 36.854 6.276c-2.548 13.787-6.302 35.535.31 35.135l3.519-.213");
}

</style>
