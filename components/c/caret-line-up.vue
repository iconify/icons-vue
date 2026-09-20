<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="gxjw4kb9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:caret-line-up" /></template>
<style>
.gxjw4kb9h {
  fill: currentColor;
  d: path("M213.66 197.66a8 8 0 0 1-11.32 0L128 123.31l-74.34 74.35a8 8 0 0 1-11.32-11.32l80-80a8 8 0 0 1 11.32 0l80 80a8 8 0 0 1 0 11.32M48 80h160a8 8 0 0 0 0-16H48a8 8 0 0 0 0 16");
}

</style>
