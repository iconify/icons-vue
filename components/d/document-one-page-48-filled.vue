<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ki_zdgbir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-one-page-48-filled" /></template>
<style>
.ki_zdgbir {
  fill: currentColor;
  d: path("M35.75 4A4.25 4.25 0 0 1 40 8.25v31.5A4.25 4.25 0 0 1 35.75 44h-23.5A4.25 4.25 0 0 1 8 39.75V8.25A4.25 4.25 0 0 1 12.25 4zm-19.5 28a1.25 1.25 0 1 0 0 2.5h15.5a1.25 1.25 0 1 0 0-2.5zm0-9a1.25 1.25 0 1 0 0 2.5h15.5a1.25 1.25 0 1 0 0-2.5zm0-9a1.25 1.25 0 1 0 0 2.5h15.5a1.25 1.25 0 1 0 0-2.5z");
}

</style>
