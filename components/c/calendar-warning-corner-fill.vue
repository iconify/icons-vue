<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j7zxgobdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-warning-corner-fill" /></template>
<style>
.j7zxgobdk {
  fill: currentColor;
  d: path("M9 4h6V3a1 1 0 0 1 2 0v1h1a3 3 0 0 1 3 3v2a1 1 0 0 1-1 1H5v9a1 1 0 0 0 1 1h3a1 1 0 0 1 0 2H6a3.004 3.004 0 0 1-3-3V7a3 3 0 0 1 3-3h1V3a1 1 0 0 1 2 0Zm9 10v4a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0m-1 6h.01a1 1 0 0 1 0 2H17a1 1 0 0 1 0-2");
}

</style>
