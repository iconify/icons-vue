<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="emen9vd1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:account-owner" /></template>
<style>
.emen9vd1i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 7.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0ZM4 21c0-2.726 1.625-4.755 4.085-5.771m9.665-1.479l1.029 2.584l2.775.18l-2.14 1.777l.687 2.695L17.75 19.5l-2.351 1.486l.687-2.695l-2.14-1.777l2.775-.18Z");
}

</style>
