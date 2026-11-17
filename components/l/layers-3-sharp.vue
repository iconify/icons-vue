<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i8bozfohd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:layers-3-sharp" /></template>
<style>
.i8bozfohd {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.091 9.75L2 12L6.091 14.25M6.091 9.75L2 7.5L12 2L22 7.5L17.909 9.75M6.091 9.75L12 13L17.909 9.75M6.091 14.25L2 16.5L12 22L22 16.5L17.909 14.25M6.091 14.25L12 17.5L17.909 14.25M17.909 9.75L22 12L17.909 14.25");
}

</style>
