<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j16d_s8wc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:child-sponsorship" /></template>
<style>
.j16d_s8wc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 12C5 8.5 5.5 3 9 3.5c1 .1 1.6.8 2 1.5c.4-.7 1-1.4 2-1.5c3.5-.5 4 5-2 8.5Zm-8.5 2H5l3 1.5h2a1.5 1.5 0 0 1 0 3H7.5m-5 2.5h7m6.5-5.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-1.75 6c0-1.75 1.75-3 3.75-3s3.75 1.25 3.75 3");
}

</style>
