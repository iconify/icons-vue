<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="f562yeb-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-u-left-up-fill" /></template>
<style>
.f562yeb-g {
  fill: currentColor;
  d: path("M208 80v88a64 64 0 0 1-128 0V88H40a8 8 0 0 1-5.66-13.66l48-48a8 8 0 0 1 11.32 0l48 48A8 8 0 0 1 136 88H96v80a48 48 0 0 0 96 0V80a8 8 0 0 1 16 0");
}

</style>
