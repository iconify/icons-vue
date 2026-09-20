<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mtxhhjb8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:highlight-16-filled" /></template>
<style>
.mtxhhjb8p {
  fill: currentColor;
  d: path("M3 1a1 1 0 0 0-1 1v2.5A1.5 1.5 0 0 0 3.5 6q-.025 0-.05.003h.102L3.5 6h.246v.003h8.545V6h.21l-.051.003h.102L12.5 6h.001a1.5 1.5 0 0 0 1.5-1.5V2a1 1 0 0 0-1-1zm.001 6.003a2 2 0 0 0 2 1.997h6a2 2 0 0 0 2-1.997zM5.003 14.5V10h5.999v.74a1.5 1.5 0 0 1-.689 1.265l-4.54 2.916a.5.5 0 0 1-.77-.421");
}

</style>
