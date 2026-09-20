<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="rlwoq1bji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:letter-circle-h-bold" /></template>
<style>
.rlwoq1bji {
  fill: currentColor;
  d: path("M128 20a108 108 0 1 0 108 108A108.12 108.12 0 0 0 128 20m0 192a84 84 0 1 1 84-84a84.09 84.09 0 0 1-84 84m44-124v80a12 12 0 0 1-24 0v-28h-40v28a12 12 0 0 1-24 0V88a12 12 0 0 1 24 0v28h40V88a12 12 0 0 1 24 0");
}

</style>
