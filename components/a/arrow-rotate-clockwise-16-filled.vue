<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i5cm_mbhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-rotate-clockwise-16-filled" /></template>
<style>
.i5cm_mbhb {
  fill: currentColor;
  d: path("M8 3.25A4.75 4.75 0 0 0 3.25 8a.75.75 0 0 1-1.5 0a6.25 6.25 0 1 1 10.587 4.5h.913a.75.75 0 0 1 0 1.5h-2.5a.75.75 0 0 1-.75-.75v-2.5a.75.75 0 0 1 1.5 0v.461A4.75 4.75 0 0 0 8 3.25M5.75 8a2.25 2.25 0 1 1 4.5 0a2.25 2.25 0 0 1-4.5 0M8 7.25a.75.75 0 1 0 0 1.5a.75.75 0 0 0 0-1.5");
}

</style>
