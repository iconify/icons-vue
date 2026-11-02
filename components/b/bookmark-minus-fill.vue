<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zytm9fneo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bookmark-minus-fill" /></template>
<style>
.zytm9fneo {
  fill: currentColor;
  d: path("M16 3a3 3 0 0 1 3 3v12c0 .285-.076.563-.225.806c-.624 1.009-2.073.939-3.064.629a4.9 4.9 0 0 1-1.266-.603L12 17.202l-2.445 1.63a4.9 4.9 0 0 1-1.266.603c-.991.31-2.44.38-3.064-.629A1.54 1.54 0 0 1 5 18V6a3 3 0 0 1 3-3Zm-7 8h6a1 1 0 0 0 0-2H9a1 1 0 0 0 0 2");
}

</style>
