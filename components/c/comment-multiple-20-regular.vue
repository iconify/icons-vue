<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="g8d31d3mk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:comment-multiple-20-regular" /></template>
<style>
.g8d31d3mk {
  fill: currentColor;
  d: path("M14.39 4.114A3.5 3.5 0 0 1 17 7.5v6c.607-.456 1-1.182 1-2v-4A4.5 4.5 0 0 0 13.5 3h-7c-.818 0-1.544.393-2 1h9a3.5 3.5 0 0 1 .89.114M4.5 5A2.5 2.5 0 0 0 2 7.5v6A2.5 2.5 0 0 0 4.5 16H5v.995a1 1 0 0 0 1.59.808L9.057 16H13.5a2.5 2.5 0 0 0 2.5-2.5v-6A2.5 2.5 0 0 0 13.5 5zM3 7.5A1.5 1.5 0 0 1 4.5 6h9A1.5 1.5 0 0 1 15 7.5v6a1.5 1.5 0 0 1-1.5 1.5H8.73L6 16.995V15H4.5A1.5 1.5 0 0 1 3 13.5z");
}

</style>
