<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v7rwtv51b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-empty-32-filled" /></template>
<style>
.v7rwtv51b {
  fill: currentColor;
  d: path("M7.5 3A4.5 4.5 0 0 0 3 7.5V9h26V7.5A4.5 4.5 0 0 0 24.5 3zM29 11H3v13.5A4.5 4.5 0 0 0 7.5 29h17a4.5 4.5 0 0 0 4.5-4.5z");
}

</style>
