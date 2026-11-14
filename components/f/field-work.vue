<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l0uzebcom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:field-work" /></template>
<style>
.l0uzebcom {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.917 5.951C9.423 4.495 5.967 4.258 3 5v14q.375-.094.759-.166m5.44.068q.6.138 1.167.337m.374.14q.663.264 1.26.621c2.5-1.5 6-1.75 9-1V9.051m0-2.6V5a14 14 0 0 0-1.817-.325M12 18.1V20m4.243-14.364l2.121 2.121l-7.778 7.779l-2.122-2.122Zm-7.779 7.778l2.122 2.122l-3.182 1.06Z");
}

</style>
