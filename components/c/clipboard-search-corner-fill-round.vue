<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tipgvkb3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clipboard-search-corner-fill-round" /></template>
<style>
.tipgvkb3o {
  fill: currentColor;
  d: path("M15.854 4.072A5.005 5.005 0 0 1 20 9a1 1 0 0 1-2 0a3.01 3.01 0 0 0-2.21-2.896A3 3 0 0 1 13 8h-2a3 3 0 0 1-2.79-1.896A3.01 3.01 0 0 0 6 9v8a3 3 0 0 0 3 3a1 1 0 0 1 0 2a5 5 0 0 1-3.536-1.464A4.98 4.98 0 0 1 4 17V9a5.006 5.006 0 0 1 4.146-4.928A3.005 3.005 0 0 1 11 2h2c1.298 0 2.451.838 2.854 2.072m3.467 13.835l2.386 2.386a.999.999 0 1 1-1.414 1.414l-2.386-2.386a3.83 3.83 0 1 1 1.414-1.414m-2.028-.614a1.829 1.829 0 1 0-2.587-2.586a1.829 1.829 0 0 0 2.587 2.586");
}

</style>
