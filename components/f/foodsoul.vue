<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rugbt8i7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:foodsoul" /></template>
<style>
.rugbt8i7p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.311 42.5V12.982h-5.917L24 36.447l-9.394-23.465H8.689V42.5M10.73 9.583a2.041 2.041 0 1 1 2.042-2.041h26.539");
}

</style>
