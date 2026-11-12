<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_0v7bcqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:credit-card-clock-corner-fill-round" /></template>
<style>
.c_0v7bcqh {
  fill: currentColor;
  d: path("M21.901 8H2.099A5.01 5.01 0 0 1 7 4h10a5.01 5.01 0 0 1 4.901 4M10 10v9a1 1 0 0 1-1 1H7a5 5 0 0 1-5-5v-5Zm1 7a6 6 0 1 1 12 0a6 6 0 0 1-12 0m2 0a4 4 0 1 0 8 0a4 4 0 0 0-8 0m5-2v1h1a1 1 0 0 1 0 2h-2a1 1 0 0 1-1-1v-2a1 1 0 0 1 2 0");
}

</style>
