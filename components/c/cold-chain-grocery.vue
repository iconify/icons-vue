<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bojmf5bmt"/><path class="rs3k_9r8m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cold-chain-grocery" /></template>
<style>
.bojmf5bmt {
  d: path("M3 5.5h13v11H3Zm13 3h2.5l2.5 3v5h-5");
}

.rs3k_9r8m {
  d: path("M5.5 18a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM16 18a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM9.5 8.25v5.5m2.382-4.125l-4.764 2.75m4.764 0l-4.764-2.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
