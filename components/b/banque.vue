<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lvtrobcrs"/><circle class="bf_1ucieo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:banque" /></template>
<style>
.bf_1ucieo {
  cx: 33.87px;
  cy: 23.86px;
  r: 0.75px;
  fill: currentColor;
}

.lvtrobcrs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.23 33.66h11.21M20.93 43.5h19.99m-5.41-15.41l3.69-2.21l-2.96-4.98m-1.95-5.26L17.42 42.38c-5.94-3.65-7.13-13.32-2.35-20C20.55 14.74 34.88 6.87 42.33 4.5M5.67 26.47h15.41m-10.1-8.16h15.41M8.35 22.39h15.41");
}

</style>
