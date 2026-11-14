<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pu0o94bcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:henna-cone" /></template>
<style>
.pu0o94bcw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7 4.5l4 16h2l4-16m-10 0a1.25 1.25 0 0 1 2.5 0a1.25 1.25 0 0 1 2.5 0a1.25 1.25 0 0 1 2.5 0a1.25 1.25 0 0 1 2.5 0m-9 4h8");
}

</style>
