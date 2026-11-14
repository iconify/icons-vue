<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dmycwjbna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:garden-netting" /></template>
<style>
.dmycwjbna {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 3v18M21 3v18M3 4.5h18M3 15q9 6 18 0M3 4.5l13 13m-7-13l11 11m-5-11l6 6m-18 0l7.5 7.5M21 4.5l-13 13m7-13l-11 11m5-11l-6 6m18 0L13.5 18");
}

</style>
