<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ydw3i-brb"/><path class="emsrzvbwk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chain-reorg" /></template>
<style>
.emsrzvbwk {
  d: path("m10 7.5l2 2l2-2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ydw3i-brb {
  d: path("M2.5 12.5h5v5h-5Zm7 0h5v5h-5Zm7 0h5v5h-5Zm-9 2.5h2m5 0h2M5 9.5c0-5 7-5 7 0");
}

</style>
