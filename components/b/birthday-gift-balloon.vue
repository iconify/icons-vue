<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gpdp27bht"/><path class="y_62ycbqe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:birthday-gift-balloon" /></template>
<style>
.gpdp27bht {
  d: path("M3 13h10v8H3Zm10.25-5.75a3.75 4.5 0 1 0 7.5 0a3.75 4.5 0 1 0-7.5 0ZM8 13v8m-5-5h10");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y_62ycbqe {
  d: path("M17 11.75C17 14 16 15.5 17 18");
}

</style>
