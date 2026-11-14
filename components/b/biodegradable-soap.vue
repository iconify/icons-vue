<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p832-eooo"/><path class="txn35tarf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:biodegradable-soap" /></template>
<style>
.p832-eooo {
  d: path("M3.5 9.5h14a1 1 0 0 1 1 1v9a1 1 0 0 1-1 1h-14a1 1 0 0 1-1-1v-9a1 1 0 0 1 1-1Z");
}

.txn35tarf {
  d: path("M5.25 12.25h10.5v5.5H5.25ZM14 9.5c0-4 2.5-6.5 7-6.5c0 4-3 5.5-7 6.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
