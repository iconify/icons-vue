<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect transform="rotate(-45 24 24)" class="tmxqompcp"/><path class="uw2-9gb_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:e-rezept" /></template>
<style>
.tmxqompcp {
  width: 44.974px;
  height: 17.75px;
  x: 1.513px;
  y: 15.125px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 8.875px;
}

.uw2-9gb_c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m36.551 24l3.35 3.35a8.875 8.875 0 0 1 0 12.55a8.875 8.875 0 0 1-12.552 0L8.1 20.65a8.875 8.875 0 0 1 0-12.55a8.875 8.875 0 0 1 12.552 0L24 11.448");
}

</style>
