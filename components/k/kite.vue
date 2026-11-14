<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x9rx84ijy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:kite" /></template>
<style>
.x9rx84ijy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 2.5l6 5l-6 7l-6-7Zm0 0v12m-6-7h12m-6 7q0 5 5 6.5m-5.25-2.5l2-1.25m.75 4l1.25-2");
}

</style>
