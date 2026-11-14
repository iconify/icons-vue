<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="br2x60bdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:kantha-quilt" /></template>
<style>
.br2x60bdg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 6v-.5A2.5 2.5 0 0 1 5.5 3H6m12 0h.5A2.5 2.5 0 0 1 21 5.5V6m0 12v.5a2.5 2.5 0 0 1-2.5 2.5H18M6 21h-.5A2.5 2.5 0 0 1 3 18.5V18M8.5 3h2.25m2.5 0h2.25m-7 18h2.25m2.5 0h2.25M3 8.5v2.25m0 2.5v2.25m18-7v2.25m0 2.5v2.25M6.25 6.25h4.25v4.25H6.25Zm7.25 0h4.25v4.25H13.5ZM6.25 13.5h4.25v4.25H6.25Zm7.25 0h4.25v4.25H13.5Z");
}

</style>
