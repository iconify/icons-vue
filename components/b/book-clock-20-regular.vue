<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m33g3widx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:book-clock-20-regular" /></template>
<style>
.m33g3widx {
  fill: currentColor;
  d: path("M4 4v12a2 2 0 0 0 2 2h9.5a.5.5 0 0 0 0-1H6a1 1 0 0 1-1-1h10a1 1 0 0 0 1-1V4a2 2 0 0 0-2-2H6a2 2 0 0 0-2 2m10-1a1 1 0 0 1 1 1v11H5V4a1 1 0 0 1 1-1zm-4 3a3 3 0 1 0 0 6a3 3 0 0 0 0-6M6 9a4 4 0 1 1 8 0a4 4 0 0 1-8 0m4-1.5a.5.5 0 0 0-1 0v2a.5.5 0 0 0 .5.5H11a.5.5 0 0 0 0-1h-1z");
}

</style>
