<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="svufz5bvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-data-bar-32-regular" /></template>
<style>
.svufz5bvf {
  fill: currentColor;
  d: path("M19 22a2 2 0 0 1 2 2v5a2 2 0 1 1-4 0v-5a2 2 0 0 1 2-2m5-6a2 2 0 0 1 2 2v11a2 2 0 1 1-4 0V18a2 2 0 0 1 2-2m5 4a2 2 0 0 1 2 2v7a2 2 0 1 1-4 0v-7a2 2 0 0 1 2-2M24.5 3A4.5 4.5 0 0 1 29 7.5v11c-.537 0-1.046.12-1.5.336V18c0-.66-.183-1.276-.5-1.803V11H5v13.5A2.5 2.5 0 0 0 7.5 27h8v2h-8A4.5 4.5 0 0 1 3 24.5v-17A4.5 4.5 0 0 1 7.5 3zm-17 2A2.5 2.5 0 0 0 5 7.5V9h22V7.5A2.5 2.5 0 0 0 24.5 5z");
}

</style>
