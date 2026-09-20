<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="szxgjzbyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-word-16-regular" /></template>
<style>
.szxgjzbyw {
  fill: currentColor;
  d: path("M7.571 7C8.361 7 9 7.64 9 8.429v5.142C9 14.361 8.36 15 7.571 15H2.43C1.639 15 1 14.36 1 13.571V8.43C1 7.639 1.64 7 2.429 7zm2.015-6a1.5 1.5 0 0 1 1.06.44l2.914 2.914a1.5 1.5 0 0 1 .44 1.06V13a2 2 0 0 1-2 2H9.496c.22-.291.379-.63.454-1H12a1 1 0 0 0 1-1V6h-2.5A1.5 1.5 0 0 1 9 4.5V2H6a1 1 0 0 0-1 1v3H4V3a2 2 0 0 1 2-2zM6.923 8.501L6.3 11.8l-.664-3.3H4.334L3.7 11.8l-.638-3.3H2l1.035 5h1.299l.666-3l.636 3l1.287-.001L8 8.5zM10 4.5a.5.5 0 0 0 .5.5h2.293L10 2.207z");
}

</style>
