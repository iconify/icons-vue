<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="j2uwl_mlt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-line-up-right" /></template>
<style>
.j2uwl_mlt {
  fill: currentColor;
  d: path("M224 216a8 8 0 0 1-8 8H40a8 8 0 0 1 0-16h176a8 8 0 0 1 8 8M80 176a8 8 0 0 0 5.66-2.34L184 75.31V152a8 8 0 0 0 16 0V56a8 8 0 0 0-8-8H96a8 8 0 0 0 0 16h76.69l-98.35 98.34A8 8 0 0 0 80 176");
}

</style>
