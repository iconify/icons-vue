<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qqg4p5x8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-data-bar-16-filled" /></template>
<style>
.qqg4p5x8j {
  fill: currentColor;
  d: path("M12 6h2v2a2 2 0 0 0-2-2M2 6h10a2 2 0 0 0-2 2v2.268A2 2 0 0 0 7 12v2H4.5A2.5 2.5 0 0 1 2 11.5zm9.5-4A2.5 2.5 0 0 1 14 4.5V5H2v-.5A2.5 2.5 0 0 1 4.5 2zm.5 5a1 1 0 0 0-1 1v7a1 1 0 1 0 2 0V8a1 1 0 0 0-1-1m-3 4a1 1 0 0 0-1 1v3a1 1 0 1 0 2 0v-3a1 1 0 0 0-1-1m5-1a1 1 0 1 1 2 0v5a1 1 0 1 1-2 0z");
}

</style>
