<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="zezijccsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-line-left-thin" /></template>
<style>
.zezijccsd {
  fill: currentColor;
  d: path("M228 128a4 4 0 0 1-4 4H81.66l65.17 65.17a4 4 0 0 1-5.66 5.66l-72-72a4 4 0 0 1 0-5.66l72-72a4 4 0 1 1 5.66 5.66L81.66 124H224a4 4 0 0 1 4 4M40 36a4 4 0 0 0-4 4v176a4 4 0 0 0 8 0V40a4 4 0 0 0-4-4");
}

</style>
