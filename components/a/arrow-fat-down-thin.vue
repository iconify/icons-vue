<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="pqqmrrbhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-fat-down-thin" /></template>
<style>
.pqqmrrbhu {
  fill: currentColor;
  d: path("M227.7 134.47A4 4 0 0 0 224 132h-44V48a12 12 0 0 0-12-12H88a12 12 0 0 0-12 12v84H32a4 4 0 0 0-2.83 6.83l96 96a4 4 0 0 0 5.66 0l96-96a4 4 0 0 0 .87-4.36M128 226.34L41.66 140H80a4 4 0 0 0 4-4V48a4 4 0 0 1 4-4h80a4 4 0 0 1 4 4v88a4 4 0 0 0 4 4h38.34Z");
}

</style>
