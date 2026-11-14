<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wfa-2cbyv"/><path class="s8-fj2bft"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chat-support" /></template>
<style>
.s8-fj2bft {
  d: path("M10.25 9.25a2.25 2.25 0 1 1 2.25 2.25v.75m0 3h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wfa-2cbyv {
  d: path("M8.25 18.75a8.5 8.5 0 1 0-3-3L3.5 20.5Z");
}

</style>
