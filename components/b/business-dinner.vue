<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mfzhg_0sy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:business-dinner" /></template>
<style>
.mfzhg_0sy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 15.5a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0ZM2.5 11v2.25a1.5 1.5 0 0 0 3 0V11M4 14.75V21m15.75 0V11c1.25 1 1.75 2.5 1.75 4.5h-1.75M10 2.5h5c0 2.5-1 4-2.5 4S10 5 10 2.5Zm2.5 4v1.75");
}

</style>
