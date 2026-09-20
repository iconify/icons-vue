<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w-g_csl8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:circle-multiple-concentric-20-filled" /></template>
<style>
.w-g_csl8m {
  fill: currentColor;
  d: path("M3.5 10a6.5 6.5 0 1 1 13 0a6.5 6.5 0 0 1-13 0M10 2a8 8 0 1 0 0 16a8 8 0 0 0 0-16m-3.5 8a3.5 3.5 0 1 1 7 0a3.5 3.5 0 0 1-7 0M10 5a5 5 0 1 0 0 10a5 5 0 0 0 0-10");
}

</style>
