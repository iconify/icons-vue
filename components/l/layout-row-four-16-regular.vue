<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g-kbwbbzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-row-four-16-regular" /></template>
<style>
.g-kbwbbzf {
  fill: currentColor;
  d: path("M14 4.5A2.5 2.5 0 0 0 11.5 2h-7A2.5 2.5 0 0 0 2 4.5v7A2.5 2.5 0 0 0 4.5 14h7a2.5 2.5 0 0 0 2.5-2.5zM11.5 3A1.5 1.5 0 0 1 13 4.5H3A1.5 1.5 0 0 1 4.5 3zM3 8.5h10v2H3zm0-1v-2h10v2zM4.5 13A1.5 1.5 0 0 1 3 11.5h10a1.5 1.5 0 0 1-1.5 1.5z");
}

</style>
