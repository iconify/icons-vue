<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ujmo2hbmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-clockwise-16-regular" /></template>
<style>
.ujmo2hbmc {
  fill: currentColor;
  d: path("M3 8a5 5 0 0 1 9-3h-2a.5.5 0 0 0 0 1h3a.5.5 0 0 0 .5-.5v-3a.5.5 0 0 0-1 0v1.531a6 6 0 1 0 1.476 4.513a.5.5 0 0 0-.996-.089A5 5 0 0 1 3 8");
}

</style>
