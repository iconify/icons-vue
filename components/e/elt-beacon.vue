<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nonp66abo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:elt-beacon" /></template>
<style>
.nonp66abo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 14h9v7h-9Zm4.5 0V7m2.298-1.928a3 3 0 0 1 .3 3.428m1.998-5.357a6 6 0 0 1 .6 6.857M9.402 8.5a3 3 0 0 1 .3-3.428M6.804 10a6 6 0 0 1 .6-6.857");
}

</style>
