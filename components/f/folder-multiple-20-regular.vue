<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w2i110bpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:folder-multiple-20-regular" /></template>
<style>
.w2i110bpy {
  fill: currentColor;
  d: path("M16.991 7.76A3 3 0 0 1 18 10v2a5 5 0 0 1-5 5H7c-.892 0-1.692-.39-2.241-1.008Q4.879 16 5 16h8a4 4 0 0 0 4-4V8q0-.12-.008-.24M6.88 3a2 2 0 0 1 1.414.586L9.707 5H13a3 3 0 0 1 3 3v4a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3zm1.414 4.414A2 2 0 0 1 6.879 8H3v4a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2V8a2 2 0 0 0-2-2H9.707zM5 4a2 2 0 0 0-2 2v1h3.879a1 1 0 0 0 .707-.293L8.793 5.5L7.586 4.293A1 1 0 0 0 6.879 4z");
}

</style>
