<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p23sfwabi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hedge-trimmer-pole" /></template>
<style>
.p23sfwabi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 21l6.25-6.25m-1.078-1.043l3.535-3.535l2.121 2.121l-3.535 3.535Zm4.578-2.457L20.5 3.5m-7.25 4.25l3 3m-.5-5.5l3 3m-.5-5.5l3 3");
}

</style>
