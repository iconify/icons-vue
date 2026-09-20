<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="s-b088sta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:apple-podcasts-logo-bold" /></template>
<style>
.s-b088sta {
  fill: currentColor;
  d: path("M161.36 130a40 40 0 1 0-66.72 0a28.4 28.4 0 0 0-4.52 4.51a27.86 27.86 0 0 0-5.42 23.67l12.75 56A27.87 27.87 0 0 0 124.77 236h6.46a27.87 27.87 0 0 0 27.32-21.79l12.75-56a27.86 27.86 0 0 0-5.42-23.67a28.4 28.4 0 0 0-4.52-4.54M128 92a16 16 0 1 1-16 16a16 16 0 0 1 16-16m19.89 60.88l-12.74 56a4 4 0 0 1-3.92 3.12h-6.46a4 4 0 0 1-3.92-3.12l-12.74-56a3.92 3.92 0 0 1 .77-3.37A4 4 0 0 1 112 148h32a4 4 0 0 1 3.15 1.51a3.92 3.92 0 0 1 .74 3.37M236 128a107.88 107.88 0 0 1-38 82.21A12 12 0 0 1 182.47 192a84 84 0 1 0-108.94 0A12 12 0 0 1 58 210.21A108 108 0 1 1 236 128");
}

</style>
