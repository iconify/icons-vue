<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="xijfvse7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrows-left-right-thin" /></template>
<style>
.xijfvse7w {
  fill: currentColor;
  d: path("M210.83 173.17a4 4 0 0 1 0 5.66l-32 32a4 4 0 0 1-5.66-5.66L198.34 180H48a4 4 0 0 1 0-8h150.34l-25.17-25.17a4 4 0 0 1 5.66-5.66ZM77.17 114.83a4 4 0 0 0 5.66-5.66L57.66 84H208a4 4 0 0 0 0-8H57.66l25.17-25.17a4 4 0 0 0-5.66-5.66l-32 32a4 4 0 0 0 0 5.66Z");
}

</style>
