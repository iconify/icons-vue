<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vlyvg4but"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:beterdichtbij" /></template>
<style>
.vlyvg4but {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.964 5.5L24.055 17.15L12.066 5.5M42.5 11.667l-11.428 11.61L42.5 35.288M36.085 42.5l-12.03-11.73l-12.23 11.73M5.5 11.266l11.708 12.01L5.5 35.45");
}

</style>
