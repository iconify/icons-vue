<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tx0crrbkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:capping-machine" /></template>
<style>
.tx0crrbkg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 21.5V14a2 2 0 0 1 2-2v-1.5h4V12a2 2 0 0 1 2 2v7.5Zm1.75-14h4.5v3h-4.5ZM6 2.5h12v5H6Z");
}

</style>
