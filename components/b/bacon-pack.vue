<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qzuim9b1a"/><path class="bp7trtb7b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bacon-pack" /></template>
<style>
.bp7trtb7b {
  d: path("M6.5 16c2.5-1.5 1-6.5 4-8m-.25 8c2.5-1.5 1-6.5 4-8M14 16c2.5-1.5 1-6.5 4-8");
}

.qzuim9b1a {
  d: path("M4 5h16l1.5 1.75L20 8.5l1.5 1.75L20 12l1.5 1.75L20 15.5l1.5 1.75L20 19H4l-1.5-1.75L4 15.5l-1.5-1.75L4 12l-1.5-1.75L4 8.5L2.5 6.75Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
