<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="oij577b1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:alarm-bold" /></template>
<style>
.oij577b1h {
  fill: currentColor;
  d: path("M128 36a100 100 0 1 0 100 100A100.11 100.11 0 0 0 128 36m0 176a76 76 0 1 1 76-76a76.08 76.08 0 0 1-76 76M32.49 72.49a12 12 0 1 1-17-17l32-32a12 12 0 1 1 17 17Zm208 0a12 12 0 0 1-17 0l-32-32a12 12 0 1 1 17-17l32 32a12 12 0 0 1 0 17M176 124a12 12 0 0 1 0 24h-48a12 12 0 0 1-12-12V88a12 12 0 0 1 24 0v36Z");
}

</style>
