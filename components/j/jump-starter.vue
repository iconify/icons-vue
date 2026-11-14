<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tff1mnd4f"/><path class="pmjh49bxn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:jump-starter" /></template>
<style>
.pmjh49bxn {
  d: path("M9.75 10.25L6 15h3l-1 3l4-4.5H9Z");
}

.tff1mnd4f {
  d: path("M2.5 7.5h13v13h-13Zm2.25 0V5h2.5v2.5m3.5 0V5h2.5v2.5M15.5 11H18a2 2 0 0 1 2 2v3.5m-1.75 0h3.5L21 21h-2Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
