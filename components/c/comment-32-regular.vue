<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d4z99xbmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:comment-32-regular" /></template>
<style>
.d4z99xbmp {
  fill: currentColor;
  d: path("M2 7.5A4.5 4.5 0 0 1 6.5 3h19A4.5 4.5 0 0 1 30 7.5v12a4.5 4.5 0 0 1-4.5 4.5h-7.631l-6.571 5.603C9.999 30.71 8 29.787 8 28.08V24H6.5A4.5 4.5 0 0 1 2 19.5zM6.5 5A2.5 2.5 0 0 0 4 7.5v12A2.5 2.5 0 0 0 6.5 22H9a1 1 0 0 1 1 1v5.081l6.851-5.842A1 1 0 0 1 17.5 22h8a2.5 2.5 0 0 0 2.5-2.5v-12A2.5 2.5 0 0 0 25.5 5z");
}

</style>
