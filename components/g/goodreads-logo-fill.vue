<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="pvgak95cx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:goodreads-logo-fill" /></template>
<style>
.pvgak95cx {
  fill: currentColor;
  d: path("M200 24H56a16 16 0 0 0-16 16v176a16 16 0 0 0 16 16h144a16 16 0 0 0 16-16V40a16 16 0 0 0-16-16m-24 136a48 48 0 0 1-86.4 28.8a8 8 0 1 1 12.8-9.6A32 32 0 0 0 160 160v-12.26A48 48 0 0 1 80 112v-8a48 48 0 0 1 80-35.74V64a8 8 0 0 1 16 0Zm-16-56v8a32 32 0 0 1-64 0v-8a32 32 0 0 1 64 0");
}

</style>
