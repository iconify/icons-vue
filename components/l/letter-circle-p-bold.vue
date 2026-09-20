<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="tzre68qig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:letter-circle-p-bold" /></template>
<style>
.tzre68qig {
  fill: currentColor;
  d: path("M128 20a108 108 0 1 0 108 108A108.12 108.12 0 0 0 128 20m0 192a84 84 0 1 1 84-84a84.09 84.09 0 0 1-84 84m8-136h-32a12 12 0 0 0-12 12v80a12 12 0 0 0 24 0v-12h20a40 40 0 0 0 0-80m0 56h-20v-32h20a16 16 0 0 1 0 32");
}

</style>
