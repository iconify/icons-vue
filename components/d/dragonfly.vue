<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qtq0b-22l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dragonfly" /></template>
<style>
.qtq0b-22l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM12 6.75V21.5m-9.5-12a4.75 1.75 0 1 0 9.5 0a4.75 1.75 0 1 0-9.5 0Zm9.5 0a4.75 1.75 0 1 0 9.5 0a4.75 1.75 0 1 0-9.5 0Zm-9 6a4.5 1.75 0 1 0 9 0a4.5 1.75 0 1 0-9 0Zm9 0a4.5 1.75 0 1 0 9 0a4.5 1.75 0 1 0-9 0Z");
}

</style>
