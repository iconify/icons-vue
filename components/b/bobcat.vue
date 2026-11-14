<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yjmcpoils"/><path class="y6l0v_bfz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bobcat" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y6l0v_bfz {
  d: path("M11 15.75h2L12 17Z");
}

.yjmcpoils {
  d: path("m6.5 9l-1-4.5L10 7h4l4.5-2.5l-1 4.5c1.5 1.5 2 3 2 4.5l2 2l-2.5.5c-1.5 3.5-4 5-7 5s-5.5-1.5-7-5l-2.5-.5l2-2c0-1.5.5-3 2-4.5Zm-1-4.5l-.5-2m13.5 2l.5-2m-9.5 10h.01m4.99 0h.01");
}

</style>
