<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhyl3_xqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cloud-moon-lightning-sharp" /></template>
<style>
.jhyl3_xqy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.16 14.1a3.02 3.02 0 0 1-.41-6.02a4.35 4.35 0 0 1 8.05-1.04a3.4 3.4 0 0 1-.45 7.06Zm-5.71-1.71a4.75 4.75 0 0 1 2.59-8.37m-.5 2.5l-.19-1.331l.7-1.149m6.7 12.71l-2.25 2.5h3.25l-2 2");
}

</style>
