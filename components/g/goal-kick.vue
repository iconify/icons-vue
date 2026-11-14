<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cpxbfwwgv"/><path class="rgthi3wvc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:goal-kick" /></template>
<style>
.cpxbfwwgv {
  d: path("M8 12.5a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0ZM2.5 19h19m-19-9h2.75M2.5 14h2.75");
}

.rgthi3wvc {
  d: path("m14.5 10l2.25 1.75L16 14.5h-3l-.75-2.75Zm0 0V6m2.25 5.75l4-1.25m-4.75 4l2.25 3.25M13 14.5l-2.25 3.25m1.5-6l-4-1.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
