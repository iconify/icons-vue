<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gw8h1abuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-copy-16-regular" /></template>
<style>
.gw8h1abuu {
  fill: currentColor;
  d: path("M6.999 1a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2H12a2 2 0 0 0 2-2V5.5h-.002V4.414a1.5 1.5 0 0 0-.439-1.06l-1.914-1.915A1.5 1.5 0 0 0 10.585 1zM12 12H6.999a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1h3v1.5a1.5 1.5 0 0 0 1.5 1.5h1.5v1.061H13V11a1 1 0 0 1-1 1m.791-8h-1.293a.5.5 0 0 1-.5-.5V2.207zM3 4a1 1 0 0 1 1-1v8a3 3 0 0 0 3 3h5a1 1 0 0 1-1 1H6.79A3.79 3.79 0 0 1 3 11.21z");
}

</style>
