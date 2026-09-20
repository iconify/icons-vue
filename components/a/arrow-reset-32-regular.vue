<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ji2zgwbse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-reset-32-regular" /></template>
<style>
.ji2zgwbse {
  fill: currentColor;
  d: path("M8.707 3.293a1 1 0 0 1 0 1.414L5.414 8H17.5C23.299 8 28 12.701 28 18.5S23.299 29 17.5 29S7 24.299 7 18.5a1 1 0 1 1 2 0a8.5 8.5 0 1 0 8.5-8.5H5.414l3.293 3.293a1 1 0 1 1-1.414 1.414l-5-5a1 1 0 0 1 0-1.414l5-5a1 1 0 0 1 1.414 0");
}

</style>
