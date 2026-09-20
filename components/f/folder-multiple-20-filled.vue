<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xnah9370h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:folder-multiple-20-filled" /></template>
<style>
.xnah9370h {
  fill: currentColor;
  d: path("M16.991 7.76A3 3 0 0 1 18 10v2a5 5 0 0 1-5 5H7c-.892 0-1.692-.39-2.241-1.008Q4.879 16 5 16h8a4 4 0 0 0 4-4V8q0-.12-.008-.24M13 5a3 3 0 0 1 3 3v4a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V8h4.879a2 2 0 0 0 1.414-.586L10.707 5zM6.879 3a2 2 0 0 1 1.414.586L9.5 4.793L7.586 6.707A1 1 0 0 1 6.879 7H2V6a3 3 0 0 1 3-3z");
}

</style>
