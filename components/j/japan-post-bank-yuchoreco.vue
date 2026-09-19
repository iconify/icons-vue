<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j8i2o_blh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:japan-post-bank-yuchoreco" /></template>
<style>
.j8i2o_blh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 14.2c-10.462 0-18.94 8.22-19.498 18.54a1.005 1.005 0 0 0 1.003 1.06h7.642c.519 0 .952-.393 1.002-.909c.487-5.11 4.632-9.142 9.851-9.142s9.364 4.032 9.851 9.142c.05.516.483.91 1.002.91h7.642a1.005 1.005 0 0 0 1.004-1.06C42.939 22.418 34.463 14.2 24 14.2m6.318 11.782l6-7.428m-3.612 10.22l8.271-4.776M24 23.749V14.2");
}

</style>
