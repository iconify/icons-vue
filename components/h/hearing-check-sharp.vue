<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pb1b-k7-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hearing-check-sharp" /></template>
<style>
.pb1b-k7-w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 8.25a5 5 0 0 1 10 0c0 2.75-2 4-2.75 5.5C10.25 15.5 10 18 7.25 18H5.21l-.56-2M6.5 8.5a2.25 2.25 0 0 1 4.5 0c0 1.25-1.25 1.75-1.75 2.75M16 7.5l2.683 3l-2.683 3m2.75-7.75a7 7 0 0 1 0 9.5");
}

</style>
