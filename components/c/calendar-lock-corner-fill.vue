<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xle5mqh0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-lock-corner-fill" /></template>
<style>
.xle5mqh0h {
  fill: currentColor;
  d: path("M9 4h6V3a1 1 0 0 1 2 0v1h1a3 3 0 0 1 3 3v2a1 1 0 0 1-1 1H5v9a1 1 0 0 0 1 1h3a1 1 0 0 1 0 2H6a3.004 3.004 0 0 1-3-3V7a3 3 0 0 1 3-3h1V3a1 1 0 0 1 2 0Zm13 13v3a2 2 0 0 1-2 2h-6a2 2 0 0 1-2-2v-3a2 2 0 0 1 2-2a3 3 0 1 1 6 0a2 2 0 0 1 2 2m-6-2h2a1 1 0 0 0-2 0m-2 2v3h6v-3Z");
}

</style>
