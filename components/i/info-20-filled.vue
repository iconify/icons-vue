<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s-5jqdbmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:info-20-filled" /></template>
<style>
.s-5jqdbmf {
  fill: currentColor;
  d: path("M18 10a8 8 0 1 0-16 0a8 8 0 0 0 16 0M9.508 8.91a.5.5 0 0 1 .984 0L10.5 9v4.502l-.008.09a.5.5 0 0 1-.984 0l-.008-.09V9zM9.25 6.75a.75.75 0 1 1 1.5 0a.75.75 0 0 1-1.5 0");
}

</style>
