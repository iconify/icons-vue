<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jeez5ei_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:hourglass-one-quarter-20-filled" /></template>
<style>
.jeez5ei_y {
  fill: currentColor;
  d: path("M6.68 14q-.212.28-.36.6A3.4 3.4 0 0 0 6 16h8a3.5 3.5 0 0 0-.31-1.4a3.4 3.4 0 0 0-.367-.6z");
}

</style>
