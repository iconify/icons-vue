<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l6bkzduca"/><path class="wn-0x-agw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:kombucha" /></template>
<style>
.l6bkzduca {
  d: path("M8.5 2.5h7V5c2.25.5 3.5 1.75 3.5 4v10a2.5 2.5 0 0 1-2.5 2.5h-9A2.5 2.5 0 0 1 5 19V9c0-2.25 1.25-3.5 3.5-4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wn-0x-agw {
  d: path("M8 9.75h8v3.5H8ZM5 11.5h3m8 0h3m-9 5h.01m3.99 2h.01");
}

</style>
