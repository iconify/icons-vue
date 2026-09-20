<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y3ysa2s1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-previous-24-filled" /></template>
<style>
.y3ysa2s1y {
  fill: currentColor;
  d: path("M6 3a1 1 0 0 0-.993.883L5 4v16a1 1 0 0 0 1.993.117L7 20V4a1 1 0 0 0-1-1m12.707.293a1 1 0 0 0-1.32-.083l-.094.083l-8 8a1 1 0 0 0-.083 1.32l.083.094l8 8a1 1 0 0 0 1.497-1.32l-.083-.094L11.414 12l7.293-7.293a1 1 0 0 0 0-1.414");
}

</style>
