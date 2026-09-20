<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j3c8u4b-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-today-20-regular" /></template>
<style>
.j3c8u4b-f {
  fill: currentColor;
  d: path("M14.5 3A2.5 2.5 0 0 1 17 5.5v9a2.5 2.5 0 0 1-2.5 2.5h-3v-1h3a1.5 1.5 0 0 0 1.5-1.5V7H4v7.5A1.5 1.5 0 0 0 5.5 16h3v1h-3A2.5 2.5 0 0 1 3 14.5v-9A2.5 2.5 0 0 1 5.5 3zm0 1h-9A1.5 1.5 0 0 0 4 5.5V6h12v-.5A1.5 1.5 0 0 0 14.5 4M11 9a1 1 0 1 1-2 0a1 1 0 0 1 2 0m.884 5.07a.5.5 0 0 1-.704.064l-.68-.566V17.5a.5.5 0 1 1-1 0v-3.932l-.68.566a.5.5 0 0 1-.64-.768l1.5-1.25a.5.5 0 0 1 .64 0l1.5 1.25a.5.5 0 0 1 .064.704");
}

</style>
