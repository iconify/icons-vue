<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="htx9o3b2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:dna-bold" /></template>
<style>
.htx9o3b2n {
  fill: currentColor;
  d: path("M204 204.5V232a12 12 0 0 1-24 0v-27.5a59.68 59.68 0 0 0-33.17-53.67l-48.4-24.2A83.54 83.54 0 0 1 52 51.5V24a12 12 0 0 1 24 0v27.5a59.68 59.68 0 0 0 33.17 53.67l48.4 24.2A83.54 83.54 0 0 1 204 204.5m-52-.5H76a59.8 59.8 0 0 1 2.34-16h56.2a12 12 0 0 0 0-24H91.76c1-1.1 2-2.18 3.13-3.21a12 12 0 0 0-16.45-17.48A84.38 84.38 0 0 0 52 204.5V232a12 12 0 0 0 24 0v-4h76a12 12 0 0 0 0-24m40-192a12 12 0 0 0-12 12v4h-76a12 12 0 0 0 0 24h76a59.8 59.8 0 0 1-2.34 16h-56.22a12 12 0 0 0 0 24h42.8c-1 1.1-2 2.18-3.13 3.21a12 12 0 0 0 16.45 17.48A84.38 84.38 0 0 0 204 51.5V24a12 12 0 0 0-12-12");
}

</style>
