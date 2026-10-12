<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="sxsey2b_i"/><path class="a0y77nbtb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chain-padlock-sharp" /></template>
<style>
.a0y77nbtb {
  d: path("M14.25 13.25V11a2.25 2.25 0 0 1 4.5 0v2.25m-6 0h7.5v8h-7.5zm3.75 3V18");
}

.sxsey2b_i {
  d: path("m8.9 5.16l.89.89l.959.794l1.76-1.76l-.959-.794l-.89-.89l-.959-.794l-1.76 1.76zm2.65.89l.71.71m0 1.76l.89.89l.959.794l1.76-1.76l-.959-.794l-.89-.89l-.959-.794l-1.76 1.76z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
