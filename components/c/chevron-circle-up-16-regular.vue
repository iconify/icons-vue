<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q3qmhmbuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-circle-up-16-regular" /></template>
<style>
.q3qmhmbuz {
  fill: currentColor;
  d: path("M8 1a7 7 0 1 1 0 14A7 7 0 0 1 8 1m0 1a6 6 0 1 0 0 12A6 6 0 0 0 8 2m-.354 3.646a.5.5 0 0 1 .708 0l3 3a.5.5 0 1 1-.707.708L8 6.707L5.354 9.354a.5.5 0 1 1-.708-.708z");
}

</style>
