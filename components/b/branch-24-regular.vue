<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="edw62vb6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:branch-24-regular" /></template>
<style>
.edw62vb6l {
  fill: currentColor;
  d: path("M4 5.5a3.5 3.5 0 1 1 4.489 3.358a5.5 5.5 0 0 0 5.261 3.892h.33a3.501 3.501 0 0 1 6.92.75a3.5 3.5 0 0 1-6.92.75h-.33a6.99 6.99 0 0 1-5.5-2.67v3.5A3.501 3.501 0 0 1 7.5 22a3.5 3.5 0 0 1-.75-6.92V8.92A3.5 3.5 0 0 1 4 5.5m3.5-2a2 2 0 1 0 0 4a2 2 0 0 0 0-4m0 13a2 2 0 1 0 0 4a2 2 0 0 0 0-4m8-3a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

</style>
