<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vih9kjbnv"/><path class="bqt1v9bkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kanadrill" /></template>
<style>
.bqt1v9bkz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.81 12.49C18.27 14 24.85 14.8 41 9m-7.77 7C31.48 22.6 23.59 40 11 40C-.83 40 7.3 23.12 27.05 21.45c21.94-1.86 17 12.32 6.78 20");
}

.vih9kjbnv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.9 5.83C23.15 16 21.19 24.64 24.32 42.17");
}

</style>
