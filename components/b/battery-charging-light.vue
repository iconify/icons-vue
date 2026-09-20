<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="vu-t6gbgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:battery-charging-light" /></template>
<style>
.vu-t6gbgi {
  fill: currentColor;
  d: path("M200 58H32a22 22 0 0 0-22 22v96a22 22 0 0 0 22 22h168a22 22 0 0 0 22-22V80a22 22 0 0 0-22-22m10 118a10 10 0 0 1-10 10H32a10 10 0 0 1-10-10V80a10 10 0 0 1 10-10h168a10 10 0 0 1 10 10Zm44-80v64a6 6 0 0 1-12 0V96a6 6 0 0 1 12 0m-116.9 28.85a6 6 0 0 1 .27 5.83l-16 32a6 6 0 1 1-10.74-5.36L122.29 134H100a6 6 0 0 1-5.37-8.68l16-32a6 6 0 0 1 10.74 5.36L109.71 122H132a6 6 0 0 1 5.1 2.85");
}

</style>
