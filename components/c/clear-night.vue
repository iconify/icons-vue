<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oq-_x-4xo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:clear-night" /></template>
<style>
.oq-_x-4xo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 4.5a8 8 0 1 0 7.5 10a6.5 6.5 0 0 1-7.5-10Zm6.5-2v4m-2-2h4m-1 5v3M18 11h3");
}

</style>
