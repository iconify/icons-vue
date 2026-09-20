<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="qu23vdbix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-up-left-thin" /></template>
<style>
.qu23vdbix {
  fill: currentColor;
  d: path("M194.83 194.83a4 4 0 0 1-5.66 0L68 73.66V168a4 4 0 0 1-8 0V64a4 4 0 0 1 4-4h104a4 4 0 0 1 0 8H73.66l121.17 121.17a4 4 0 0 1 0 5.66");
}

</style>
