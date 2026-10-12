<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h0p55620y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:first-mile-sharp" /></template>
<style>
.h0p55620y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 12h7.5v7.5h-7.5zm3.75 0v3m2-3V9m0-5.5h6l-.6.8l-1.4 1.95l1.4 1.95l.6.8h-6Zm4.75 16h2.25m3 0h2.25");
}

</style>
