<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nth5xubin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:botanist" /></template>
<style>
.nth5xubin {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.172 20.5H4c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5c.789 0 1.543.078 2.249.225M6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0ZM19 21.5v-5m0 1.5c-2.25 0-3.5-1.5-3.5-3.25C17.75 14.75 19 16 19 18Zm0-1.5c0-2 1.25-3.5 3-3.5c0 2-1.25 3.5-3 3.5Z");
}

</style>
