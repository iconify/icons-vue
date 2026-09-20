<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dstujcz4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-lock-32-filled" /></template>
<style>
.dstujcz4a {
  fill: currentColor;
  d: path("M7.5 3A4.5 4.5 0 0 0 3 7.5V9h26V7.5A4.5 4.5 0 0 0 24.5 3zM29 11H3v13.5A4.5 4.5 0 0 0 7.5 29h8.626A4 4 0 0 1 16 28v-6a4 4 0 0 1 3.08-3.894a5.002 5.002 0 0 1 9.84 0l.08.02zm-8.5 8.5H20a2.5 2.5 0 0 0-2.5 2.5v6a2.5 2.5 0 0 0 2.5 2.5h8a2.5 2.5 0 0 0 2.5-2.5v-6a2.5 2.5 0 0 0-2.5-2.5h-.5V19a3.5 3.5 0 1 0-7 0zm2-.5a1.5 1.5 0 0 1 3 0v.5h-3zm3.5 6a2 2 0 1 1-4 0a2 2 0 0 1 4 0");
}

</style>
