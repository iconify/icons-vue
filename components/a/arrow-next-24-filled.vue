<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_o6a-b1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-next-24-filled" /></template>
<style>
.p_o6a-b1y {
  fill: currentColor;
  d: path("M18 3a1 1 0 0 1 .993.883L19 4v16a1 1 0 0 1-1.993.117L17 20V4a1 1 0 0 1 1-1m-12.707.293a1 1 0 0 1 1.32-.083l.094.083l8 8a1 1 0 0 1 .083 1.32l-.083.094l-8 8a1 1 0 0 1-1.497-1.32l.083-.094L12.586 12L5.293 4.707a1 1 0 0 1 0-1.414");
}

</style>
