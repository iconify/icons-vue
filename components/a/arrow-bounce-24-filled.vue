<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h2y0ikqvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-bounce-24-filled" /></template>
<style>
.h2y0ikqvc {
  fill: currentColor;
  d: path("M11 7a1 1 0 0 0-1-1H3a1 1 0 0 0-1 1v7a1 1 0 1 0 2 0V9.414l8.043 8.043a1 1 0 0 0 1.414 0l8.25-8.25a1 1 0 0 0-1.414-1.414l-7.543 7.543L5.414 8H10a1 1 0 0 0 1-1");
}

</style>
