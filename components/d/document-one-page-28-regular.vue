<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="inwac7bag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-one-page-28-regular" /></template>
<style>
.inwac7bag {
  fill: currentColor;
  d: path("M21.25 2A2.75 2.75 0 0 1 24 4.75v18.5A2.75 2.75 0 0 1 21.25 26H6.75A2.75 2.75 0 0 1 4 23.25V4.75A2.75 2.75 0 0 1 6.75 2zM6.75 3.5c-.69 0-1.25.56-1.25 1.25v18.5c0 .69.56 1.25 1.25 1.25h14.5c.69 0 1.25-.56 1.25-1.25V4.75c0-.69-.56-1.25-1.25-1.25zM19.25 19a.75.75 0 0 1 0 1.5H8.75a.75.75 0 0 1 0-1.5zm0-6a.75.75 0 0 1 0 1.5H8.75a.75.75 0 0 1 0-1.5zm0-6a.75.75 0 0 1 0 1.5H8.75a.75.75 0 0 1 0-1.5z");
}

</style>
