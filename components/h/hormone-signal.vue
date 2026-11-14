<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z9xbewg0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hormone-signal" /></template>
<style>
.z9xbewg0z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 3s-6 7-6 11a6 6 0 0 0 12 0c0-4-6-11-6-11Zm7.794 6.5a9 9 0 0 1 0 9M18.83 7.117a12 12 0 0 1 0 13.766");
}

</style>
