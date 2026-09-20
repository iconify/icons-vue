<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yj3htgi8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-rotate-clockwise-20-regular" /></template>
<style>
.yj3htgi8k {
  fill: currentColor;
  d: path("M10 3a7 7 0 0 1 3.602 13H16a.5.5 0 0 1 0 1h-3.5a.5.5 0 0 1-.5-.5V13a.5.5 0 0 1 1 0v2.191A5.99 5.99 0 0 0 16 10a6 6 0 0 0-12 0a.5.5 0 0 1-1 0a7 7 0 0 1 7-7m0 5a2 2 0 1 1 0 4a2 2 0 0 1 0-4m0 1a1 1 0 1 0 0 2a1 1 0 0 0 0-2");
}

</style>
