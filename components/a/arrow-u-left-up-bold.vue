<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="nfyblidny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-u-left-up-bold" /></template>
<style>
.nfyblidny {
  fill: currentColor;
  d: path("M212 80v88a68 68 0 0 1-136 0V61L48.49 88.49a12 12 0 0 1-17-17l48-48a12 12 0 0 1 17 0l48 48a12 12 0 0 1-17 17L100 61v107a44 44 0 0 0 88 0V80a12 12 0 0 1 24 0");
}

</style>
