<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="juxcvoaqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:beaver-dam" /></template>
<style>
.juxcvoaqu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 3.5h10V7H7ZM4.5 7h15v3.5h-15Zm-2 3.5h19V14h-19ZM3 18q2.25-1.875 4.5 0t4.5 0t4.5 0t4.5 0");
}

</style>
