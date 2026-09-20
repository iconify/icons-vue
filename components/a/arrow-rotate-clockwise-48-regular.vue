<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d_1e4gb7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-rotate-clockwise-48-regular" /></template>
<style>
.d_1e4gb7y {
  fill: currentColor;
  d: path("M24 6c9.941 0 18 8.059 18 18c0 6.6-3.553 12.367-8.849 15.5h5.599a1.25 1.25 0 1 1 0 2.5h-8.5c-.69 0-1.25-.56-1.25-1.25v-8.5a1.25 1.25 0 1 1 2.5 0v5.316c4.77-2.642 8-7.727 8-13.566c0-8.56-6.94-15.5-15.5-15.5S8.5 15.44 8.5 24A1.25 1.25 0 1 1 6 24c0-9.941 8.059-18 18-18m0 12a6 6 0 1 1 0 12a6 6 0 0 1 0-12m0 2.5a3.5 3.5 0 1 0 0 7a3.5 3.5 0 0 0 0-7");
}

</style>
