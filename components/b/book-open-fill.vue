<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uc5826bqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:book-open-fill" /></template>
<style>
.uc5826bqw {
  fill: currentColor;
  d: path("M9.293 18.707C8.98 18.395 8.468 18 8 18H5a3 3 0 0 1-3-3V7a3 3 0 0 1 3-3h3a4.99 4.99 0 0 1 4 1.998A4.99 4.99 0 0 1 16 4h3a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3h-3c-.468 0-.98.395-1.293.707l-2 2a1 1 0 0 1-1.414 0ZM13 10a1 1 0 0 0-2 0v5a1 1 0 0 0 2 0Z");
}

</style>
