<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i22_eobya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:grease-gun" /></template>
<style>
.i22_eobya {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 8.5h11v7H6ZM3 10h3v4H3Zm6-1.5v-3h5m3 6.5h1.5a2.5 2.5 0 0 1 2.5 2.5V19");
}

</style>
