<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="hv4lrf-fc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:article-ny-times-fill" /></template>
<style>
.hv4lrf-fc {
  fill: currentColor;
  d: path("M216 40H40a16 16 0 0 0-16 16v144a16 16 0 0 0 16 16h176a16 16 0 0 0 16-16V56a16 16 0 0 0-16-16M64 92a8 8 0 0 1-16 0V80a8 8 0 0 1 8-8h72a8 8 0 0 1 8 8v12a8 8 0 0 1-16 0v-4h-20v48h4a8 8 0 0 1 0 16H80a8 8 0 0 1 0-16h4V88H64Zm136 92H80a8 8 0 0 1 0-16h120a8 8 0 0 1 0 16m0-32h-64a8 8 0 0 1 0-16h64a8 8 0 0 1 0 16m0-32h-48a8 8 0 0 1 0-16h48a8 8 0 0 1 0 16");
}

</style>
