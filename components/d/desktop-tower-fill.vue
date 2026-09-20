<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="pxplbgbac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:desktop-tower-fill" /></template>
<style>
.pxplbgbac {
  fill: currentColor;
  d: path("M120 76v112a4 4 0 0 1-4 4H96v16h15.73a8.18 8.18 0 0 1 8.25 7.47a8 8 0 0 1-8 8.53H64.27a8.18 8.18 0 0 1-8.27-7.47a8 8 0 0 1 8-8.53h16v-16H32a24 24 0 0 1-24-24V96a24 24 0 0 1 24-24h84a4 4 0 0 1 4 4m128-28v160a16 16 0 0 1-16 16h-80a16 16 0 0 1-16-16V48a16 16 0 0 1 16-16h80a16 16 0 0 1 16 16m-44.1 133.57a12 12 0 1 0-10.34 10.33a12 12 0 0 0 10.34-10.33m20.1-78.1a8.18 8.18 0 0 0-8.27-7.47h-47.46a8.18 8.18 0 0 0-8.25 7.47a8 8 0 0 0 8 8.53h48a8 8 0 0 0 7.98-8.53m0-32a8.18 8.18 0 0 0-8.27-7.47h-47.46a8.18 8.18 0 0 0-8.27 7.47a8 8 0 0 0 8 8.53h48a8 8 0 0 0 8-8.53");
}

</style>
