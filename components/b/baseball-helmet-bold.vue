<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="usu586bpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:baseball-helmet-bold" /></template>
<style>
.usu586bpp {
  fill: currentColor;
  d: path("M120 156a32 32 0 1 0-32 32a32 32 0 0 0 32-32m-40 0a8 8 0 1 1 8 8a8 8 0 0 1-8-8m164-40h-16.66A108 108 0 0 0 12 128v24a76.08 76.08 0 0 0 76 76h40a76.08 76.08 0 0 0 76-76v-12h40a12 12 0 0 0 0-24M36 152v-24a84 84 0 0 1 167.15-12H152a12 12 0 0 0-12 12v24a52 52 0 0 1-104 0m144 0a52.07 52.07 0 0 1-33.67 48.65A75.63 75.63 0 0 0 164 152v-12h16Z");
}

</style>
