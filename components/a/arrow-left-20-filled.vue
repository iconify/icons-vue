<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nsj63wb8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-left-20-filled" /></template>
<style>
.nsj63wb8z {
  fill: currentColor;
  d: path("M8.73 16.795a.75.75 0 0 0 1.031-1.09L4.522 10.75h12.724a.75.75 0 0 0 0-1.5H4.52l5.241-4.957a.75.75 0 1 0-1.03-1.09l-6.417 6.07a1 1 0 0 0-.3.566a.75.75 0 0 0 0 .329a1 1 0 0 0 .3.558z");
}

</style>
