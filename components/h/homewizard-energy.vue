<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ye5ag5bzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:homewizard-energy" /></template>
<style>
.ye5ag5bzb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.92 38.382h10.218m-5.108-5.109V43.49m-19.692.01L37.14 18.698H25.76L36.903 4.5H24.33c-1.25 0-2.405.667-3.03 1.75L10.86 24.333h8.94z");
}

</style>
