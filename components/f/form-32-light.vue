<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l6e8jybex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:form-32-light" /></template>
<style>
.l6e8jybex {
  fill: currentColor;
  d: path("M24.5 3A4.5 4.5 0 0 1 29 7.5v17a4.5 4.5 0 0 1-4.5 4.5h-17A4.5 4.5 0 0 1 3 24.5v-17A4.5 4.5 0 0 1 7.5 3zm-17 1A3.5 3.5 0 0 0 4 7.5v17A3.5 3.5 0 0 0 7.5 28h17a3.5 3.5 0 0 0 3.5-3.5v-17A3.5 3.5 0 0 0 24.5 4zM10 19.5a3 3 0 1 1 0 6a3 3 0 0 1 0-6m0 1a2 2 0 1 0 0 4a2 2 0 0 0 0-4M24.5 22a.5.5 0 0 1 0 1h-9a.5.5 0 0 1 0-1zM10 11.5a3 3 0 1 1 0 6a3 3 0 0 1 0-6m0 1a2 2 0 1 0 0 4a2 2 0 0 0 0-4M24.5 14a.5.5 0 0 1 0 1h-9a.5.5 0 0 1 0-1zm0-6a.5.5 0 0 1 0 1h-17a.5.5 0 0 1 0-1z");
}

</style>
