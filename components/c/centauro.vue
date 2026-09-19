<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hrho4zb_m"/><path class="i7tdfgbcr"/><path class="np_ts570w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:centauro" /></template>
<style>
.hrho4zb_m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 9c-16.253 0-39 10.024-39 19.702C4.5 35 12.127 39 24 39c1.613 0 5.966 0 7.974-.538l3.084-7.882c-1.968.527-14.144.924-14.144-4.838c0-7.35 17.997-12.317 20.292-12.317zM32.166 30.854L27.941 39");
}

.i7tdfgbcr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.984 35.881c-3.911.937-22.985.436-22.985-8.171c0-10.94 25.897-17.5 32.873-17.5");
}

.np_ts570w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.164 32.866c-3.385.662-18.281.404-18.281-6.217c0-9.354 23.882-15.041 26.265-15.041");
}

</style>
