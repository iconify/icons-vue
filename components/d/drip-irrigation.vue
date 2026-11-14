<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zrai4pbfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:drip-irrigation" /></template>
<style>
.zrai4pbfw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4h19m-16 3C6.5 8.25 7 9.25 7 10.25a1.5 1.5 0 0 1-3 0c0-1 .5-2 1.5-3.25ZM12 7c1 1.25 1.5 2.25 1.5 3.25a1.5 1.5 0 0 1-3 0c0-1 .5-2 1.5-3.25Zm6.5 0c1 1.25 1.5 2.25 1.5 3.25a1.5 1.5 0 0 1-3 0c0-1 .5-2 1.5-3.25Zm-13 13.5v-4l-2-2m2 2l2-2m4.5 6v-4l-2-2m2 2l2-2m4.5 6v-4l-2-2m2 2l2-2");
}

</style>
