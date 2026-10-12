<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v2m-sjbqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hoverboard-sharp" /></template>
<style>
.v2m-sjbqt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.04 11.75H10v-1h4v1h2.96a2.5 2.5 0 1 1 0 3.5H7.04a2.5 2.5 0 1 1 0-3.5Z");
}

</style>
