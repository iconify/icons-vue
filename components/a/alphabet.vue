<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w75w3cbbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:alphabet" /></template>
<style>
.w75w3cbbi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.75 20.25l4.75-16l4.75 16m-7.75-5.5h6M15 4.25v16m0-3a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

</style>
