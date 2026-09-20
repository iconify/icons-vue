<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f8gkixb4s"/><path class="o8z-2ybyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:de-bijenkorf" /></template>
<style>
.f8gkixb4s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.62 35.788v-21.5L24 3.538L5.38 14.288v21.5L24 46.538z");
}

.o8z-2ybyp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 46.538V33.012H9.873V26.97h6.166v-8.44A7.96 7.96 0 0 1 24 10.566v-7.03");
}

</style>
