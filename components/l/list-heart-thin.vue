<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="xqv2yec7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:list-heart-thin" /></template>
<style>
.xqv2yec7f {
  fill: currentColor;
  d: path("M36 64a4 4 0 0 1 4-4h176a4 4 0 0 1 0 8H40a4 4 0 0 1-4-4m4 68h64a4 4 0 0 0 0-8H40a4 4 0 0 0 0 8m80 56H40a4 4 0 0 0 0 8h80a4 4 0 0 0 0-8m124-44c0 14.51-8.56 29-25.44 43.07a143.5 143.5 0 0 1-24.77 16.51a4 4 0 0 1-3.58 0a143.5 143.5 0 0 1-24.77-16.51C148.56 173 140 158.51 140 144a28 28 0 0 1 52-14.41A28 28 0 0 1 244 144m-8 0a20 20 0 0 0-40 0a4 4 0 0 1-8 0a20 20 0 0 0-40 0c0 25.8 35.54 46.83 44 51.47c8.46-4.64 44-25.67 44-51.47");
}

</style>
