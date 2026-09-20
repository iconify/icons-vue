<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="kvx2wsbuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:list-bullets-light" /></template>
<style>
.kvx2wsbuz {
  fill: currentColor;
  d: path("M82 64a6 6 0 0 1 6-6h128a6 6 0 0 1 0 12H88a6 6 0 0 1-6-6m134 58H88a6 6 0 0 0 0 12h128a6 6 0 0 0 0-12m0 64H88a6 6 0 0 0 0 12h128a6 6 0 0 0 0-12M44 54a10 10 0 1 0 10 10a10 10 0 0 0-10-10m0 128a10 10 0 1 0 10 10a10 10 0 0 0-10-10m0-64a10 10 0 1 0 10 10a10 10 0 0 0-10-10");
}

</style>
