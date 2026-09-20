<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="r--vul73e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:chat-teardrop-slash-fill" /></template>
<style>
.r--vul73e {
  fill: currentColor;
  d: path("M213.92 210.62a8 8 0 1 1-11.84 10.76l-13.57-14.92A99.4 99.4 0 0 1 132 224H48a16 16 0 0 1-16-16v-84a99.54 99.54 0 0 1 23.29-64.08L42.08 45.38a8 8 0 0 1 .72-11.46a8.22 8.22 0 0 1 11.34.95Zm-5.57-29.91a4 4 0 0 0 6.24-.4A100 100 0 0 0 83.78 36.42a4 4 0 0 0-1 6.18Z");
}

</style>
