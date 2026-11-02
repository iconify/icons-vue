<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="za171bbwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bookmark-bulk" /></template>
<style>
.za171bbwu {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 3h8a3 3 0 0 1 3 3v12c0 .285-.076.563-.225.806c-.624 1.009-2.073.939-3.064.629a4.9 4.9 0 0 1-1.266-.603L12 17.202l-2.445 1.63a4.9 4.9 0 0 1-1.266.603c-.991.31-2.44.38-3.064-.629A1.54 1.54 0 0 1 5 18V6a3 3 0 0 1 3-3");
}

</style>
