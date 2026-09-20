<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="lrf8mlbsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:frame-corners-light" /></template>
<style>
.lrf8mlbsa {
  fill: currentColor;
  d: path("M198 80v32a6 6 0 0 1-12 0V86h-26a6 6 0 0 1 0-12h32a6 6 0 0 1 6 6M96 170H70v-26a6 6 0 0 0-12 0v32a6 6 0 0 0 6 6h32a6 6 0 0 0 0-12M230 56v144a14 14 0 0 1-14 14H40a14 14 0 0 1-14-14V56a14 14 0 0 1 14-14h176a14 14 0 0 1 14 14m-12 0a2 2 0 0 0-2-2H40a2 2 0 0 0-2 2v144a2 2 0 0 0 2 2h176a2 2 0 0 0 2-2Z");
}

</style>
