<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t-2rdh-1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-rotate-counterclockwise-16-regular" /></template>
<style>
.t-2rdh-1m {
  fill: currentColor;
  d: path("M8 2a6 6 0 0 1 6 6a.5.5 0 0 1-1 0a5 5 0 1 0-8 4v-1.5a.5.5 0 0 1 1 0V13a.5.5 0 0 1-.5.5H3a.5.5 0 0 1 0-1h1.031A6 6 0 0 1 8 2m0 4a2 2 0 1 1 0 4a2 2 0 0 1 0-4m0 1a1 1 0 1 0 0 2a1 1 0 0 0 0-2");
}

</style>
