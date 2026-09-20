<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q7hh2wbfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:headset-32-regular" /></template>
<style>
.q7hh2wbfy {
  fill: currentColor;
  d: path("M6 12C6 6.477 10.477 2 16 2s10 4.477 10 10v6a4 4 0 0 1-4 4h-2a2 2 0 0 1-2-2v-6a2 2 0 0 1 2-2h4a8 8 0 1 0-16 0h4a2 2 0 0 1 2 2v6a2 2 0 0 1-2 2H8a4 4 0 0 0 4 4h1.17a3.001 3.001 0 1 1 0 2H12a6 6 0 0 1-6-6zm2 2v6h4v-6zm16 0h-4v6h2a2 2 0 0 0 2-2zm-7 13a1 1 0 1 0-2 0a1 1 0 0 0 2 0");
}

</style>
