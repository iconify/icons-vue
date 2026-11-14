<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wag2yxudr"/><path class="za8zq0uzq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:broadcast-tower" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wag2yxudr {
  d: path("m6.5 21.5l5.5-14l5.5 14");
}

.za8zq0uzq {
  d: path("M10.5 6a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm-1.25 8.5h5.5m1.08-11.714a5 5 0 0 1 0 6.428m-7.66 0a5 5 0 0 1 0-6.428");
}

</style>
