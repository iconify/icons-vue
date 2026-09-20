<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="hd1ruac2g"/><path class="m4ycjb8cj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:lectern-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hd1ruac2g {
  d: path("M232 136H24a8 8 0 0 1-7.16-11.58l40-80A8 8 0 0 1 64 40h128a8 8 0 0 1 7.16 4.42l40 80A8 8 0 0 1 232 136");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m4ycjb8cj {
  d: path("m246.3 120.84l-40-80A15.92 15.92 0 0 0 192 32H64a15.92 15.92 0 0 0-14.3 8.84l-40 80A16 16 0 0 0 24 144h96v64H96a8 8 0 0 0 0 16h64a8 8 0 0 0 0-16h-24v-64h96a16 16 0 0 0 14.31-23.16ZM24 128l40-80h128l40 80Zm168-24a8 8 0 0 1-8 8H72a8 8 0 0 1 0-16h112a8 8 0 0 1 8 8");
}

</style>
