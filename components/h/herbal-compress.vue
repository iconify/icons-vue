<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xhkyfwbwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:herbal-compress" /></template>
<style>
.xhkyfwbwn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 12.5L7.5 8h9L14 12.5c5 1.5 5.5 9-2 9s-7-7.5-2-9Zm-1.5 0h7M12 8V2.5m0 2.75c.5-2 2-2.75 4.5-2.75c-.5 2-2 2.75-4.5 2.75Z");
}

</style>
