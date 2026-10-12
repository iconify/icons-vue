<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jpmakxb5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fog-light-sharp" /></template>
<style>
.jpmakxb5q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.25 5.5c3.9 0 7 2.9 7 6.5s-3.1 6.5-7 6.5H12.5v-13zM3.25 9l6.5-1m-6.5 5.5l6.5-1M3.25 18l6.5-1M6.5 5c-1 1.5 1 3 0 4.5s1 3 0 4.5s1 3 0 4.5");
}

</style>
