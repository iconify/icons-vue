<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d6n3iobyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-gantt-fill" /></template>
<style>
.d6n3iobyf {
  fill: currentColor;
  d: path("M4 4v14a1 1 0 0 0 1 1h16a1 1 0 0 1 0 2H5a3 3 0 0 1-3-3V4a1 1 0 0 1 2 0m3 3h6a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2m3 4h7a1 1 0 0 1 0 2h-7a1 1 0 0 1 0-2m10 4a1 1 0 0 1 0 2h-6a1 1 0 0 1 0-2Z");
}

</style>
