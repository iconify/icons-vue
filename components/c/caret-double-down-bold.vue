<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="clls34xqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:caret-double-down-bold" /></template>
<style>
.clls34xqa {
  fill: currentColor;
  d: path("M216.49 127.51a12 12 0 0 1 0 17l-80 80a12 12 0 0 1-17 0l-80-80a12 12 0 1 1 17-17L128 199l71.51-71.52a12 12 0 0 1 16.98.03m-97 17a12 12 0 0 0 17 0l80-80a12 12 0 0 0-17-17L128 119L56.49 47.51a12 12 0 0 0-17 17Z");
}

</style>
