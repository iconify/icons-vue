<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gaislzbae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-text-48-filled" /></template>
<style>
.gaislzbae {
  fill: currentColor;
  d: path("M24 4v11.25A3.75 3.75 0 0 0 27.75 19H40v22a3 3 0 0 1-3 3H11a3 3 0 0 1-3-3V7a3 3 0 0 1 3-3zm-7.75 31a1.25 1.25 0 1 0 0 2.5h15.5a1.25 1.25 0 1 0 0-2.5zm0-6a1.25 1.25 0 1 0 0 2.5h15.5a1.25 1.25 0 1 0 0-2.5zm0-6a1.25 1.25 0 1 0 0 2.5h15.5a1.25 1.25 0 1 0 0-2.5zm23.212-6.5H27.75c-.69 0-1.25-.56-1.25-1.25V4.464z");
}

</style>
