<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="aj8x3w-0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-left-28-filled" /></template>
<style>
.aj8x3w-0n {
  fill: currentColor;
  d: path("M18.457 23.207a1 1 0 0 1-1.414 0l-8.75-8.75a1 1 0 0 1 0-1.414l8.75-8.75a1 1 0 1 1 1.414 1.414l-8.043 8.043l8.043 8.043a1 1 0 0 1 0 1.414");
}

</style>
