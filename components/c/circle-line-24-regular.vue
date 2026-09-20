<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h-c9d0bxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:circle-line-24-regular" /></template>
<style>
.h-c9d0bxm {
  fill: currentColor;
  d: path("M3.533 11.25h16.934a8.5 8.5 0 0 0-16.934 0m16.934 1.5H3.533a8.5 8.5 0 0 0 16.934 0M2 12C2 6.477 6.477 2 12 2s10 4.477 10 10s-4.477 10-10 10S2 17.523 2 12");
}

</style>
