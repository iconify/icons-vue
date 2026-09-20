<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="gkapk37fa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:chat-centered-bold" /></template>
<style>
.gkapk37fa {
  fill: currentColor;
  d: path("M216 36H40a20 20 0 0 0-20 20v128a20 20 0 0 0 20 20h58.11l12.52 21.92a20 20 0 0 0 34.74 0L157.89 204H216a20 20 0 0 0 20-20V56a20 20 0 0 0-20-20m-4 144h-61.07a12 12 0 0 0-10.42 6.05L128 207.94l-12.51-21.89a12 12 0 0 0-10.42-6.05H44V60h168Z");
}

</style>
