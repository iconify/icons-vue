<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m-gh-7b_a"/><path class="p3f1ikwug"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:directions-straight" /></template>
<style>
.m-gh-7b_a {
  d: path("M12 2.25L21.75 12L12 21.75L2.25 12Zm0 14.25v-9");
}

.p3f1ikwug {
  d: path("M9.5 10L12 7.5l2.5 2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
