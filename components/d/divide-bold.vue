<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="qhvje3e5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:divide-bold" /></template>
<style>
.qhvje3e5g {
  fill: currentColor;
  d: path("M228 128a12 12 0 0 1-12 12H40a12 12 0 0 1 0-24h176a12 12 0 0 1 12 12M128 84a20 20 0 1 0-20-20a20 20 0 0 0 20 20m0 88a20 20 0 1 0 20 20a20 20 0 0 0-20-20");
}

</style>
