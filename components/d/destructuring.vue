<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z91ajgz9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:destructuring" /></template>
<style>
.z91ajgz9q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 3.5c-2 0-2.5 1-2.5 3v3C5.5 11 4.75 12 3 12c1.75 0 2.5 1 2.5 2.5v3c0 2 .5 3 2.5 3m3-17h4v4h-4Zm5.5 6.5h4v4h-4Zm-5 7h4v4h-4Z");
}

</style>
