<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cct27-rwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:insular" /></template>
<style>
.cct27-rwu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.47 7.88H8.53L4.5 34.53h39zm-30.94 0L43.5 34.53M14.61 7.88l28.1 21.41M20.7 7.88l21.22 16.17M26.78 7.88l14.34 10.93M32.87 7.88l7.46 5.69M7.9 12.04l29.52 22.49M7.27 16.2l24.06 18.33M6.64 20.35l18.61 14.18M6.02 24.51l13.14 10.02M5.39 28.67l7.69 5.86m28.44 5.59H6.48L4.5 34.53h39z");
}

</style>
