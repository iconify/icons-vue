<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pm6r3u2jt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cat-purr" /></template>
<style>
.pm6r3u2jt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6 9l.5-5L10 7h4l3.5-3l.5 5c1 6-2 10-6 10S5 15 6 9Zm-2.5 1q-1.5 3 0 6m17-6q1.5 3 0 6m-11-4h.01m4.99 0h.01");
}

</style>
