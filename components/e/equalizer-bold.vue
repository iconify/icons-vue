<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="h1vdaxjxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:equalizer-bold" /></template>
<style>
.h1vdaxjxz {
  fill: currentColor;
  d: path("M80 108a12 12 0 0 1-12 12H28a12 12 0 0 1 0-24h40a12 12 0 0 1 12 12m-12 28H28a12 12 0 0 0 0 24h40a12 12 0 0 0 0-24m0 40H28a12 12 0 0 0 0 24h40a12 12 0 0 0 0-24m80-40h-40a12 12 0 0 0 0 24h40a12 12 0 0 0 0-24m0 40h-40a12 12 0 0 0 0 24h40a12 12 0 0 0 0-24m40-96h40a12 12 0 0 0 0-24h-40a12 12 0 0 0 0 24m40 16h-40a12 12 0 0 0 0 24h40a12 12 0 0 0 0-24m0 40h-40a12 12 0 0 0 0 24h40a12 12 0 0 0 0-24m0 40h-40a12 12 0 0 0 0 24h40a12 12 0 0 0 0-24");
}

</style>
