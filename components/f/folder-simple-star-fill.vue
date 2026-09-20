<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="li8g89ghd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:folder-simple-star-fill" /></template>
<style>
.li8g89ghd {
  fill: currentColor;
  d: path("M128 208a8 8 0 0 1-8 8H40a16 16 0 0 1-16-16V64a16 16 0 0 1 16-16h53.33a16.12 16.12 0 0 1 9.6 3.2L130.67 72H216a16 16 0 0 1 16 16v32a8 8 0 0 1-16 0V88h-88a8 8 0 0 1-4.8-1.6L93.33 64H40v136h80a8 8 0 0 1 8 8m111.63-48.8a8 8 0 0 0-7-5.56l-29.84-2.31l-11.43-26.5a8 8 0 0 0-14.7 0l-11.43 26.5l-29.84 2.31a8 8 0 0 0-4.47 14.14l22.51 18.59l-6.85 27.71a8 8 0 0 0 11.82 8.81l25.6-15.07l25.61 15.07a8 8 0 0 0 11.82-8.81l-6.85-27.71l22.51-18.59a8 8 0 0 0 2.54-8.58");
}

</style>
