<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sb3_h_bym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:doordash" /></template>
<style>
.sb3_h_bym {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m32.481 35.037l-6.954.016l-7.833-8.374l15.082-.077a2.66 2.66 0 0 0 2.646-2.66a2.66 2.66 0 0 0-2.671-2.658l-19.51.087L4.5 12.947l27.958.003A11.044 11.044 0 0 1 43.5 23.994a11.044 11.044 0 0 1-11.019 11.043");
}

</style>
