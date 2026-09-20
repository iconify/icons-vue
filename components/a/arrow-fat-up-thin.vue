<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="p2rvhdcpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-fat-up-thin" /></template>
<style>
.p2rvhdcpe {
  fill: currentColor;
  d: path("m226.83 117.17l-96-96a4 4 0 0 0-5.66 0l-96 96A4 4 0 0 0 32 124h44v84a12 12 0 0 0 12 12h80a12 12 0 0 0 12-12v-84h44a4 4 0 0 0 2.83-6.83M176 116a4 4 0 0 0-4 4v88a4 4 0 0 1-4 4H88a4 4 0 0 1-4-4v-88a4 4 0 0 0-4-4H41.66L128 29.66L214.34 116Z");
}

</style>
