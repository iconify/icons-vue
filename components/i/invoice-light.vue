<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="w1p97aclt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:invoice-light" /></template>
<style>
.w1p97aclt {
  fill: currentColor;
  d: path("M28 126a6 6 0 0 1 0-12h28a10 10 0 0 0 0-20H40a22 22 0 0 1 0-44h2v-2a6 6 0 0 1 12 0v2h10a6 6 0 0 1 0 12H40a10 10 0 0 0 0 20h16a22 22 0 0 1 0 44h-2v2a6 6 0 0 1-12 0v-2Zm202-70v136a14 14 0 0 1-14 14H40a14 14 0 0 1-14-14v-40a6 6 0 0 1 12 0v40a2 2 0 0 0 2 2h122v-36H80a6 6 0 0 1 0-12h82v-36h-58a6 6 0 0 1 0-12h114V62H96a6 6 0 0 1 0-12h128a6 6 0 0 1 6 6m-56 90h44v-36h-44Zm44 46v-34h-44v36h42a2 2 0 0 0 2-2");
}

</style>
