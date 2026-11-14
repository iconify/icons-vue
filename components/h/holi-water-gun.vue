<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l_mfw0w_k"/><path class="fmmszbcal"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:holi-water-gun" /></template>
<style>
.fmmszbcal {
  d: path("m5.569 15.692l3.031-1.75l1.634 4.83l-2.814 1.625Zm5.197-3l3.464-2l1.25 2.165l-3.464 2ZM14 2c.75 1 1.25 1.5 1.25 2.25a1.25 1.25 0 0 1-2.5 0c0-.75.5-1.25 1.25-2.25Zm5.25 0C20 3 20.5 3.5 20.5 4.25a1.25 1.25 0 0 1-2.5 0C18 3.5 18.5 3 19.25 2ZM20 8.25c.75 1 1.25 1.5 1.25 2.25a1.25 1.25 0 0 1-2.5 0c0-.75.5-1.25 1.25-2.25Z");
}

.l_mfw0w_k {
  d: path("m2.27 12.978l9.96-5.75l2 3.464l-9.96 5.75Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
