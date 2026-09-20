<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="bxphxlbix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:boat-fill" /></template>
<style>
.bxphxlbix {
  fill: currentColor;
  d: path("M221.06 110.59L208 106.23V56a16 16 0 0 0-16-16h-56V24a8 8 0 0 0-16 0v16H64a16 16 0 0 0-16 16v50.23l-13.06 4.36A16 16 0 0 0 24 125.77V152c0 61.54 97.89 86.72 102.06 87.76a8 8 0 0 0 3.88 0C134.11 238.72 232 213.54 232 152v-26.23a16 16 0 0 0-10.94-15.18M136 168a8 8 0 0 1-16 0v-63.13a8 8 0 0 1 16 0Zm56-67.1l-61.47-20.49a8 8 0 0 0-5.06 0L64 100.9V56h128Z");
}

</style>
