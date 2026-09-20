<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qt2s6mbdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-counterclockwise-32-regular" /></template>
<style>
.qt2s6mbdf {
  fill: currentColor;
  d: path("M27 16c0-6.075-4.925-11-11-11a10.96 10.96 0 0 0-7.55 3H11a1 1 0 1 1 0 2H6a1 1 0 0 1-1-1V4a1 1 0 0 1 2 0v2.62A12.96 12.96 0 0 1 16 3c7.18 0 13 5.82 13 13s-5.82 13-13 13S3 23.18 3 16q0-.546.044-1.082a1 1 0 0 1 1.994.164A11 11 0 0 0 5 16c0 6.075 4.925 11 11 11s11-4.925 11-11");
}

</style>
