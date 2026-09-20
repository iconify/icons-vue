<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="vnpyeo48y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-line-down-fill" /></template>
<style>
.vnpyeo48y {
  fill: currentColor;
  d: path("M50.34 117.66A8 8 0 0 1 56 104h64V32a8 8 0 0 1 16 0v72h64a8 8 0 0 1 5.66 13.66l-72 72a8 8 0 0 1-11.32 0ZM216 208H40a8 8 0 0 0 0 16h176a8 8 0 0 0 0-16");
}

</style>
