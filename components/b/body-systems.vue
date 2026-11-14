<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j9yzq_eqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:body-systems" /></template>
<style>
.j9yzq_eqw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.058 15.807L10 15a.781.781 0 0 0-1.5 0l-.25 3.5c0 .5-.5 1-1 1h-1c-.75 0-1.25-.5-1-1.25L6 14l.5-2l-1.25 1.5c-.25.5-.5.75-1.25.75c-1 0-1.5-.5-1.25-1.5l2-2.5C5 9 6 8.75 7.25 8.75h4c1.25 0 2.25.25 2.5 1.5l1.781 2.226m-2.122 1.302a3 3 0 0 1-.159-.278L12 12l.5 2l.05.281m-1.526 5.186c-.414-.119-.774-.543-.774-.967l-.086-1.197M7.25 4.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm10.75 10l3.75 2.25L18 18.75l-3.75-2.25Zm-3.75 5.25L18 21.75l3.75-2.25");
}

</style>
