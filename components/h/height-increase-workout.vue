<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="loqw_5acf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:height-increase-workout" /></template>
<style>
.loqw_5acf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.662 43.5V15.542h4.575L24 4.5L13.763 15.542h4.575V43.5m5.04-24.884h6.284M23.378 30h6.284m-6.284 11.836h6.284M25.5 21.462h4.162M25.5 24.308h4.162M25.5 27.154h4.162M25.5 32.96h4.162M25.5 35.918h4.162M25.5 38.877h4.162");
}

</style>
