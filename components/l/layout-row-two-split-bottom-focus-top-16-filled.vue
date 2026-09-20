<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fm50yjbtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-row-two-split-bottom-focus-top-16-filled" /></template>
<style>
.fm50yjbtr {
  fill: currentColor;
  d: path("M2 4.5A2.5 2.5 0 0 1 4.5 2h7A2.5 2.5 0 0 1 14 4.5v7a2.5 2.5 0 0 1-2.5 2.5h-7A2.5 2.5 0 0 1 2 11.5zM13 8H8.5v5h3a1.5 1.5 0 0 0 1.5-1.5zM7.5 8H3v3.5A1.5 1.5 0 0 0 4.5 13h3z");
}

</style>
