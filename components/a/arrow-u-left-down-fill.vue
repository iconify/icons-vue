<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="gqctg4b4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-u-left-down-fill" /></template>
<style>
.gqctg4b4s {
  fill: currentColor;
  d: path("M208 88v88a8 8 0 0 1-16 0V88a48 48 0 0 0-96 0v80h40a8 8 0 0 1 5.66 13.66l-48 48a8 8 0 0 1-11.32 0l-48-48A8 8 0 0 1 40 168h40V88a64 64 0 0 1 128 0");
}

</style>
