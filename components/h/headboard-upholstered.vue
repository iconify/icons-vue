<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_9mm0bgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:headboard-upholstered" /></template>
<style>
.u_9mm0bgb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 21V7a3 3 0 0 1 6 0v14m0-7h10.5a2 2 0 0 1 2 2v5M9 18h12.5M6 9.5h.01M6 14h.01");
}

</style>
