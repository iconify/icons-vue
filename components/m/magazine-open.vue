<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vtusomy8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:magazine-open" /></template>
<style>
.vtusomy8y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 6c-2-1.5-5.5-2-9-1.5V19c3.5-.5 7 0 9 1.5c2-1.5 5.5-2 9-1.5V4.5c-3.5-.5-7 0-9 1.5Zm0 0v14.5M6 9h3m6 0h3");
}

</style>
