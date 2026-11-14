<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p4v-4lgql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:floor-sweep" /></template>
<style>
.p4v-4lgql {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m19 3l-7.5 9.75m-2-1.25l4 2.5l-1 7h-9Zm-7 9.5h19m-2.75-8.5l2.75 2.75L18.75 18L16 15.25Z");
}

</style>
