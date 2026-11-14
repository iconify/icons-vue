<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="seo1c3f4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:aircraft-lavatory" /></template>
<style>
.seo1c3f4z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 2.5h5V11h-5Zm8.345 16.76L12 20.5H6L7 16c-2-1-3.5-2.5-3.5-5H17a8 8 0 0 1-.135 1.48m-1.169 2.443C14.758 15.95 13.335 16.5 11.5 16.5l.283 2.264M18.5 15.25v6.5m-3-2.25l3-2.25l3 2.25M17 21.75h3");
}

</style>
