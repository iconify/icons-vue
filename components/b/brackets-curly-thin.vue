<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="uzptvcbaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:brackets-curly-thin" /></template>
<style>
.uzptvcbaz {
  fill: currentColor;
  d: path("M35.89 128C52 136.23 52 155.64 52 172c0 24.8 1.35 40 28 40a4 4 0 0 1 0 8c-36 0-36-26.61-36-48c0-24.8-1.35-40-28-40a4 4 0 0 1 0-8c26.65 0 28-15.2 28-40c0-21.39 0-48 36-48a4 4 0 0 1 0 8c-26.65 0-28 15.2-28 40c0 16.36 0 35.77-16.11 44M240 124c-26.65 0-28-15.2-28-40c0-21.39 0-48-36-48a4 4 0 0 0 0 8c26.65 0 28 15.2 28 40c0 16.36 0 35.77 16.11 44C204 136.23 204 155.64 204 172c0 24.8-1.35 40-28 40a4 4 0 0 0 0 8c36 0 36-26.61 36-48c0-24.8 1.35-40 28-40a4 4 0 0 0 0-8");
}

</style>
