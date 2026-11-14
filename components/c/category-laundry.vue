<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f55s2igpx"/><path class="o3z9bdh6x"/><path class="mbljtd6vv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:category-laundry" /></template>
<style>
.f55s2igpx {
  d: path("M5.5 7.5h13v14h-13Z");
}

.mbljtd6vv {
  d: path("M11 16.25a1 1 0 1 0 2 0a1 1 0 1 0-2 0ZM8.5 9h.01m2.99 0h4M7.25 4a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm5.25-.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm5 .5a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

.o3z9bdh6x {
  d: path("M8.75 16.25a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0ZM5.5 10.5h13");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
