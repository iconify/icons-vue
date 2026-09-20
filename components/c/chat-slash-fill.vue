<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="in8-j-z8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:chat-slash-fill" /></template>
<style>
.in8-j-z8x {
  fill: currentColor;
  d: path("M213.92 210.61a8 8 0 1 1-11.84 10.76L189.92 208H83l-32.6 28.16l-.08.07A15.94 15.94 0 0 1 40 240a16.1 16.1 0 0 1-6.8-1.52A15.85 15.85 0 0 1 24 224V64a16 16 0 0 1 16-16h4.46l-2.38-2.62a8 8 0 1 1 11.84-10.76ZM216 48H96.75a4 4 0 0 0-3 6.69L225 199.06a4 4 0 0 0 7-2.69V64a16 16 0 0 0-16-16");
}

</style>
