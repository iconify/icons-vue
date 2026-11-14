<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ju4xunb-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bass-guitar" /></template>
<style>
.ju4xunb-w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 14.5a3.5 3.5 0 1 0 3 3a2.5 2.5 0 1 0-3-3Zm4.25-1.25L18.5 5.5m-.871-.543l2.828-2.828l1.414 1.414l-2.828 2.828ZM5 17l2 2");
}

</style>
