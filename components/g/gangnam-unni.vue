<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mr8jy9bkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gangnam-unni" /></template>
<style>
.mr8jy9bkr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 33.25a9.25 9.25 0 0 1-18.5 0V24h-9.25a9.25 9.25 0 0 1 0-18.5H42.5zM8.21 21.291l18.5 18.5");
}

</style>
