<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="t2w-jfb1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:compass-tool-fill" /></template>
<style>
.t2w-jfb1x {
  fill: currentColor;
  d: path("M215.12 123.64a8 8 0 1 0-14.24-7.28a79.6 79.6 0 0 1-33.08 33.5l-18.24-41.05A36 36 0 0 0 136 44.91V24a8 8 0 0 0-16 0v20.91a36 36 0 0 0-13.56 63.9L56.69 220.75a8 8 0 1 0 14.62 6.5l25.14-56.56A95.5 95.5 0 0 0 128 176a99.1 99.1 0 0 0 31.6-5.21l25.09 56.46a8 8 0 0 0 14.62-6.5l-25-56.25a95.8 95.8 0 0 0 40.81-40.86M128 160a79.5 79.5 0 0 1-25-4l18.08-40.68a35.8 35.8 0 0 0 13.88 0l18.14 40.8A83.2 83.2 0 0 1 128 160");
}

</style>
