<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="lpzrlwyeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:bicycle-fill" /></template>
<style>
.lpzrlwyeq {
  fill: currentColor;
  d: path("m54.46 164.71l27.87-38.21a48 48 0 1 1-12.92-9.44l-27.87 38.23a8 8 0 1 0 12.92 9.42M208 112a47.8 47.8 0 0 0-16.93 3.09L214.91 156a8 8 0 1 1-13.82 8l-23.83-40.86A48 48 0 1 0 208 112m-42.07-40H192a8 8 0 0 1 8 8a8 8 0 0 0 16 0a24 24 0 0 0-24-24h-40a8 8 0 0 0-6.91 12l11.65 20H99.26L82.91 60A8 8 0 0 0 76 56H48a8 8 0 0 0 0 16h23.41l13.71 23.51l-15.71 21.55a47.9 47.9 0 0 1 12.92 9.44l11.59-15.9l31.17 53.4a8 8 0 1 0 13.82-8l-30.32-52h57.48l11.19 19.17a48.1 48.1 0 0 1 13.81-8.08Z");
}

</style>
