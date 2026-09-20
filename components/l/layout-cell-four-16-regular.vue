<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y1wsq3j6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-cell-four-16-regular" /></template>
<style>
.y1wsq3j6d {
  fill: currentColor;
  d: path("M2 4.5A2.5 2.5 0 0 1 4.5 2h7A2.5 2.5 0 0 1 14 4.5v7a2.5 2.5 0 0 1-2.5 2.5h-7A2.5 2.5 0 0 1 2 11.5zM4.5 3A1.5 1.5 0 0 0 3 4.5v3h4.5V3zm3 5.5H3v3A1.5 1.5 0 0 0 4.5 13h3zm1 0V13h3a1.5 1.5 0 0 0 1.5-1.5v-3zm4.5-1v-3A1.5 1.5 0 0 0 11.5 3h-3v4.5z");
}

</style>
