<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="go8jbubji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:chat-teardrop-text-bold" /></template>
<style>
.go8jbubji {
  fill: currentColor;
  d: path("M176 108a12 12 0 0 1-12 12H96a12 12 0 0 1 0-24h68a12 12 0 0 1 12 12m-12 28H96a12 12 0 0 0 0 24h68a12 12 0 0 0 0-24m72-12a104.11 104.11 0 0 1-104 104H48a20 20 0 0 1-20-20v-84a104 104 0 0 1 208 0m-24 0a80 80 0 0 0-160 0v80h80a80.09 80.09 0 0 0 80-80");
}

</style>
