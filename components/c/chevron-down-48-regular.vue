<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w62_-1b3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-down-48-regular" /></template>
<style>
.w62_-1b3q {
  fill: currentColor;
  d: path("M8.366 16.116a1.25 1.25 0 0 0 0 1.768l14.75 14.75a1.25 1.25 0 0 0 1.768 0l14.75-14.75a1.25 1.25 0 0 0-1.768-1.768L24 29.982L10.134 16.116a1.25 1.25 0 0 0-1.768 0");
}

</style>
