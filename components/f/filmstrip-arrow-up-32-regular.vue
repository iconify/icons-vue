<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fjqi5gbad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:filmstrip-arrow-up-32-regular" /></template>
<style>
.fjqi5gbad {
  fill: currentColor;
  d: path("M23 15.5a7.5 7.5 0 1 1 0 15a7.5 7.5 0 0 1 0-15m.78 2.22a.75.75 0 0 0-1.06 0l-4 4a.75.75 0 1 0 1.06 1.06l2.72-2.72v7.69a.75.75 0 0 0 1.5 0v-7.69l2.72 2.72a.75.75 0 1 0 1.06-1.06zM25.5 4A4.5 4.5 0 0 1 30 8.5v8.845a9 9 0 0 0-2-1.83V8.5A2.5 2.5 0 0 0 25.5 6h-19A2.5 2.5 0 0 0 4 8.5v15A2.5 2.5 0 0 0 6.5 26h8.014a9 9 0 0 0 1.003 2H6.5A4.5 4.5 0 0 1 2 23.5v-15A4.5 4.5 0 0 1 6.5 4zM7 20a1 1 0 0 1 1 1v2a1 1 0 1 1-2 0v-2a1 1 0 0 1 1-1m0-6a1 1 0 0 1 1 1v2a1 1 0 1 1-2 0v-2a1 1 0 0 1 1-1m0-6a1 1 0 0 1 1 1v2a1 1 0 1 1-2 0V9a1 1 0 0 1 1-1m18 0a1 1 0 0 1 1 1v2a1 1 0 1 1-2 0V9a1 1 0 0 1 1-1");
}

</style>
