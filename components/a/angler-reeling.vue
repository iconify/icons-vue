<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="otw6d4bhw"/><path class="x8i59kblf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:angler-reeling" /></template>
<style>
.otw6d4bhw {
  d: path("M3.5 21Q10 9 20 3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x8i59kblf {
  d: path("M6.25 17a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0ZM20 3v12M9.5 17h.01");
}

</style>
