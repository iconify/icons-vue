<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n11ni4a9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:group-work" /></template>
<style>
.n11ni4a9c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 7a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm10 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm-5 9a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM3 13c0-1.5 1.5-2 4-2c1 0 2 .2 2.5.5M21 13c0-1.5-1.5-2-4-2c-1 0-2 .2-2.5.5m-6 10c0-1.5 1.5-2 3.5-2s3.5.5 3.5 2");
}

</style>
