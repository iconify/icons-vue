<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kmcrezbss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:electric-guitar" /></template>
<style>
.kmcrezbss {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.75 11.75c-.5-1-.25-2.5.5-3c-2 0-3.25 1.75-4.75 2.25c-3 1-4.5 4-3.5 7.5c.75 2.5 4 3.25 6.5 2c2-1 2.75-2.75 3.5-3c.5-1.5 1.75-2.25 2.25-4.75c-.5 0-2 0-3 .5Zm.75.75l6.25-6.25m-.975-.543l3.182-3.182l1.768 1.768l-3.182 3.182ZM6.75 14.75l2.5 2.5");
}

</style>
