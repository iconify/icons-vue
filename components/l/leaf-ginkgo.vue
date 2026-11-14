<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ap3hzfb2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:leaf-ginkgo" /></template>
<style>
.ap3hzfb2z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 15.5C8 14 4 10.5 3 7c2.5-3.5 6-4.5 8-3.75l1 3.25l1-3.25c2-.75 5.5.25 8 3.75c-1 3.5-5 7-9 8.5Zm0 0c0 2.5-.5 4.5-2 6");
}

</style>
