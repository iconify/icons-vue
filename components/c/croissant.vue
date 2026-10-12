<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s3j177bys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:croissant" /></template>
<style>
.s3j177bys {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 16.5C2.75 10.75 7 6.25 12 6.25s9.25 4.5 8.5 10.25c-.1.75-.9 1-1.5.5l-3-2.5c-1.25 1.25-2.4 1.75-4 1.75s-2.75-.5-4-1.75L5 17c-.6.5-1.4.25-1.5-.5m5.75-8.25L10 13.5m4.75-5.25L14 13.5");
}

</style>
