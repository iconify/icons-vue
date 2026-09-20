<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="qdz-lvb9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:git-branch-thin" /></template>
<style>
.qdz-lvb9f {
  fill: currentColor;
  d: path("M228 64a28 28 0 1 0-32 27.71V112a12 12 0 0 1-12 12H96a19.9 19.9 0 0 0-12 4V91.71a28 28 0 1 0-8 0v72.58a28 28 0 1 0 8 0V144a12 12 0 0 1 12-12h88a20 20 0 0 0 20-20V91.71A28 28 0 0 0 228 64M60 64a20 20 0 1 1 20 20a20 20 0 0 1-20-20m40 128a20 20 0 1 1-20-20a20 20 0 0 1 20 20M200 84a20 20 0 1 1 20-20a20 20 0 0 1-20 20");
}

</style>
