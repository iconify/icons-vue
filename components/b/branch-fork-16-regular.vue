<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uo_4ubcbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:branch-fork-16-regular" /></template>
<style>
.uo_4ubcbx {
  fill: currentColor;
  d: path("M5 5.95a2.5 2.5 0 1 0-1 0v4.1a2.5 2.5 0 1 0 1 0V9h4.5A2.5 2.5 0 0 0 12 6.5v-.55a2.5 2.5 0 1 0-1 0v.55A1.5 1.5 0 0 1 9.5 8H5zM4.5 5a1.5 1.5 0 1 1 0-3a1.5 1.5 0 0 1 0 3m7 0a1.5 1.5 0 1 1 0-3a1.5 1.5 0 0 1 0 3M6 12.5a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0");
}

</style>
