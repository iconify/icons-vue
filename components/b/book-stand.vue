<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lkyfo376d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:book-stand" /></template>
<style>
.lkyfo376d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 6.5c-2.5-2-6-2.5-9-2v9c3-.5 6.5 0 9 2c2.5-2 6-2.5 9-2v-9c-3-.5-6.5 0-9 2Zm0 0v15m-4.5 0h9");
}

</style>
