<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qgb62ubid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ica" /></template>
<style>
.qgb62ubid {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5 14.764v18.472m38 0l-8.944-18.472l-6.425 13.27a9.236 9.236 0 1 1-4.015-12.211m17.486 13.494h-8.52");
}

</style>
