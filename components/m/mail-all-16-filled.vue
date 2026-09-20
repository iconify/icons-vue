<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jrq8bnsic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mail-all-16-filled" /></template>
<style>
.jrq8bnsic {
  fill: currentColor;
  d: path("M1 4a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v.201L7 7.432l-6-3.23zm6.237 4.44L13 5.337V10a2 2 0 0 1-2 2H3a2 2 0 0 1-2-2V5.337L6.763 8.44a.5.5 0 0 0 .474 0M5 14a2 2 0 0 1-1.732-1H11a3 3 0 0 0 3-3V4.268A2 2 0 0 1 15 6v4a4 4 0 0 1-4 4z");
}

</style>
