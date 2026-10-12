<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u852u-blm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:clam-sharp" /></template>
<style>
.u852u-blm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 13c0-4.75 4-8 9-8s9 3.25 9 8v2.75H3zm9-6.5V14M8.25 7.5L9.5 14m6.25-6.5L14.5 14m-9.25 4.25h13.5c-1 2-3.5 3-6.75 3s-5.75-1-6.75-3Z");
}

</style>
