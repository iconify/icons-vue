<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hfy823obj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-multiple-16-regular" /></template>
<style>
.hfy823obj {
  fill: currentColor;
  d: path("M14 6a1 1 0 0 0-1-1v6a3 3 0 0 1-3 3H5a1 1 0 0 0 1 1h4.21A3.79 3.79 0 0 0 14 11.21zM4.997 1a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2H10a2 2 0 0 0 2-2V5.5h-.002V4.414a1.5 1.5 0 0 0-.44-1.06L9.645 1.439A1.5 1.5 0 0 0 8.584 1zM10 12H4.998a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1h3v1.5a1.5 1.5 0 0 0 1.5 1.5h1.5v1.061H11V11a1 1 0 0 1-1 1m.79-8H9.499a.5.5 0 0 1-.5-.5V2.207z");
}

</style>
