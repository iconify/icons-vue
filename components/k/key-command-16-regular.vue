<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="e3r02mbec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:key-command-16-regular" /></template>
<style>
.e3r02mbec {
  fill: currentColor;
  d: path("M6 4v1h4V4a2 2 0 1 1 2 2h-1v4h1a2 2 0 1 1-2 2v-1H6v1a2 2 0 1 1-2-2h1V6H4a2 2 0 1 1 2-2M5 5V4a1 1 0 1 0-1 1zm5 5V6H6v4zm1 1v1a1 1 0 1 0 1-1zm1-6a1 1 0 1 0-1-1v1zm-7 6H4a1 1 0 1 0 1 1z");
}

</style>
