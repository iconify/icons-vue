<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mfl__cbam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cheque-stub" /></template>
<style>
.mfl__cbam {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 6H4a1.5 1.5 0 0 0-1.5 1.5v9A1.5 1.5 0 0 0 4 18h4.5l-.75-1.5l.75-1.5l-.75-1.5l.75-1.5l-.75-1.5L8.5 9l-.75-1.5Zm4-.5h7a2 2 0 0 1 2 2v9a2 2 0 0 1-2 2h-7m-1-13v1.25m0 2.75v1.25m0 2.5v1.25m0 2.75v1.25m3-9h4m-4 5H17");
}

</style>
