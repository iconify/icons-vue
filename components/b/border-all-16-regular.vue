<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fppqb4p2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:border-all-16-regular" /></template>
<style>
.fppqb4p2h {
  fill: currentColor;
  d: path("M2 4.5A2.5 2.5 0 0 1 4.5 2h7A2.5 2.5 0 0 1 14 4.5v7a2.5 2.5 0 0 1-2.5 2.5h-7A2.5 2.5 0 0 1 2 11.5zM4.5 3A1.5 1.5 0 0 0 3 4.5v3h4.5V3zm4 0v4.5H13v-3A1.5 1.5 0 0 0 11.5 3zM13 8.5H8.5V13h3a1.5 1.5 0 0 0 1.5-1.5zM7.5 13V8.5H3v3A1.5 1.5 0 0 0 4.5 13z");
}

</style>
