<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g33dgwb0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-row-two-split-top-16-regular" /></template>
<style>
.g33dgwb0x {
  fill: currentColor;
  d: path("M2 4.5A2.5 2.5 0 0 1 4.5 2h7A2.5 2.5 0 0 1 14 4.5v7a2.5 2.5 0 0 1-2.5 2.5h-7A2.5 2.5 0 0 1 2 11.5zM4.5 3A1.5 1.5 0 0 0 3 4.5v3h4.5V3zm4 4.5H13v-3A1.5 1.5 0 0 0 11.5 3h-3zm4.5 1H3v3A1.5 1.5 0 0 0 4.5 13h7a1.5 1.5 0 0 0 1.5-1.5z");
}

</style>
