<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="vtpzgebdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:gender-nonbinary-bold" /></template>
<style>
.vtpzgebdl {
  fill: currentColor;
  d: path("M140 93V69.2l21.83 13.09a12 12 0 1 0 12.34-20.58L151.32 48l22.85-13.71a12 12 0 0 0-12.34-20.58L128 34L94.17 13.71a12 12 0 0 0-12.34 20.58L104.68 48L81.83 61.71a12 12 0 1 0 12.34 20.58L116 69.2V93a76 76 0 1 0 24 0m-12 127a52 52 0 1 1 52-52a52.06 52.06 0 0 1-52 52");
}

</style>
