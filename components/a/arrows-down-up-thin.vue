<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="bh8c0gi6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrows-down-up-thin" /></template>
<style>
.bh8c0gi6u {
  fill: currentColor;
  d: path("M114.83 173.17a4 4 0 0 1 0 5.66l-32 32a4 4 0 0 1-5.66 0l-32-32a4 4 0 0 1 5.66-5.66L76 198.34V48a4 4 0 0 1 8 0v150.34l25.17-25.17a4 4 0 0 1 5.66 0m96-96l-32-32a4 4 0 0 0-5.66 0l-32 32a4 4 0 0 0 5.66 5.66L172 57.66V208a4 4 0 0 0 8 0V57.66l25.17 25.17a4 4 0 1 0 5.66-5.66");
}

</style>
