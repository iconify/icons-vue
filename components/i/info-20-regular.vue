<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="oi5wyabdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:info-20-regular" /></template>
<style>
.oi5wyabdz {
  fill: currentColor;
  d: path("M10.492 8.91A.5.5 0 0 0 9.5 9v4.502l.008.09a.5.5 0 0 0 .992-.09V9zm.307-2.16a.75.75 0 1 0-1.5 0a.75.75 0 0 0 1.5 0M18 10a8 8 0 1 0-16 0a8 8 0 0 0 16 0M3 10a7 7 0 1 1 14 0a7 7 0 0 1-14 0");
}

</style>
