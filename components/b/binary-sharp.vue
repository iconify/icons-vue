<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h5zy7xh3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:binary-sharp" /></template>
<style>
.h5zy7xh3v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16 2.75h2.5v4.5a2.5 2.5 0 0 1-5 0v-4.5zm-8 11.5h2.5v4.5a2.5 2.5 0 0 1-5 0v-4.5zM7.25 4L9 2.75v7m6.25 5.75L17 14.25v7");
}

</style>
