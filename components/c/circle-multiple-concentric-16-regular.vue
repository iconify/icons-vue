<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mlkcbfjpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:circle-multiple-concentric-16-regular" /></template>
<style>
.mlkcbfjpd {
  fill: currentColor;
  d: path("M2 8a6 6 0 1 1 12 0A6 6 0 0 1 2 8m6-7a7 7 0 1 0 0 14A7 7 0 0 0 8 1M5 8a3 3 0 1 1 6 0a3 3 0 0 1-6 0m3-4a4 4 0 1 0 0 8a4 4 0 0 0 0-8");
}

</style>
