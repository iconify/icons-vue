<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="o-c81mpkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-rtl-12-filled" /></template>
<style>
.o-c81mpkg {
  fill: currentColor;
  d: path("M10.95 3A2.5 2.5 0 0 0 8.5 1h-5a2.5 2.5 0 0 0-2.45 2zM11 4v4.5A2.5 2.5 0 0 1 8.5 11h-5A2.5 2.5 0 0 1 1 8.5V4zM9 5.5a.5.5 0 1 0-1 0a.5.5 0 0 0 1 0m0 2a.5.5 0 1 0-1 0a.5.5 0 0 0 1 0M6.5 5a.5.5 0 1 0 0 1a.5.5 0 0 0 0-1M7 7.5a.5.5 0 1 0-1 0a.5.5 0 0 0 1 0M4.5 5a.5.5 0 1 0 0 1a.5.5 0 0 0 0-1");
}

</style>
