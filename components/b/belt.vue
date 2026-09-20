<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="yi9tokplu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:belt" /></template>
<style>
.yi9tokplu {
  fill: currentColor;
  d: path("M248 160h-56V96h56a8 8 0 0 0 0-16h-58.17A16 16 0 0 0 176 72h-64a16 16 0 0 0-13.83 8H64a8 8 0 0 0-16 0H8a8 8 0 0 0 0 16h40v64H8a8 8 0 0 0 0 16h40a8 8 0 0 0 16 0h34.17a16 16 0 0 0 13.83 8h64a16 16 0 0 0 13.83-8H248a8 8 0 0 0 0-16M64 96h32v64H64Zm48 72V88h64v32h-32a8 8 0 0 0 0 16h32v32Z");
}

</style>
