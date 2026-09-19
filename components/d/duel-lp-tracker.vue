<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c7l9ndbli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:duel-lp-tracker" /></template>
<style>
.c7l9ndbli {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 7a6 6 0 0 0-6 6a6 6 0 0 0 .547 2.5H5.5L24 41l18.5-25.5H29.453A6 6 0 0 0 30 13a6 6 0 0 0-6-6m0 3.25a3 3 0 0 1 3 3a3 3 0 0 1-1.037 2.25h-3.926A3 3 0 0 1 21 13.25a3 3 0 0 1 3-3");
}

</style>
