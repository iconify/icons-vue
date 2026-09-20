<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gz87xwbhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-cell-four-focus-top-left-16-filled" /></template>
<style>
.gz87xwbhn {
  fill: currentColor;
  d: path("M4.5 2A2.5 2.5 0 0 0 2 4.5v7A2.5 2.5 0 0 0 4.5 14h7a2.5 2.5 0 0 0 2.5-2.5v-7A2.5 2.5 0 0 0 11.5 2zM3 8.5h4.5V13h-3A1.5 1.5 0 0 1 3 11.5zm10 0v3a1.5 1.5 0 0 1-1.5 1.5h-3V8.5zm-4.5-1V3h3A1.5 1.5 0 0 1 13 4.5v3z");
}

</style>
