<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rwwfpsbiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:art-restoration" /></template>
<style>
.rwwfpsbiw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.25 12.25l2-2C13 7.5 16.5 5.5 19.5 4.5c-1 3-3 6.5-5.75 8.25l-2 2Zm2-2l2.5 2.5m-3.25.75l-6 6m2-16l.75 2.25l2.25.75l-2.25.75L6.5 9.5l-.75-2.25L3.5 6.5l2.25-.75Z");
}

</style>
