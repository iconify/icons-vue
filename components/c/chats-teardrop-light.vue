<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="af1s9_b_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:chats-teardrop-light" /></template>
<style>
.af1s9_b_g {
  fill: currentColor;
  d: path("M168.16 74.42A78 78 0 0 0 18 104v64a14 14 0 0 0 14 14h56a78.15 78.15 0 0 0 72 48h64a14 14 0 0 0 14-14v-64a78 78 0 0 0-69.84-77.58M30 168v-64a66 66 0 1 1 66 66H32a2 2 0 0 1-2-2m196 48a2 2 0 0 1-2 2h-64a66.13 66.13 0 0 1-58.89-36.19a77.92 77.92 0 0 0 71-94.68A66 66 0 0 1 226 152Z");
}

</style>
