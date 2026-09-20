<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="m972snb4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:book-open-text-thin" /></template>
<style>
.m972snb4e {
  fill: currentColor;
  d: path("M232 52h-72a36 36 0 0 0-32 19.54A36 36 0 0 0 96 52H24a4 4 0 0 0-4 4v144a4 4 0 0 0 4 4h72a28 28 0 0 1 28 28a4 4 0 0 0 8 0a28 28 0 0 1 28-28h72a4 4 0 0 0 4-4V56a4 4 0 0 0-4-4M96 196H28V60h68a28 28 0 0 1 28 28v121.4A35.94 35.94 0 0 0 96 196m132 0h-68a35.94 35.94 0 0 0-28 13.41V88a28 28 0 0 1 28-28h68ZM160 92h40a4 4 0 0 1 0 8h-40a4 4 0 0 1 0-8m44 36a4 4 0 0 1-4 4h-40a4 4 0 0 1 0-8h40a4 4 0 0 1 4 4m0 32a4 4 0 0 1-4 4h-40a4 4 0 0 1 0-8h40a4 4 0 0 1 4 4");
}

</style>
