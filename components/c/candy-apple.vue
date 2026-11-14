<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hpve99q8p"/><path class="qj1lnacwz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:candy-apple" /></template>
<style>
.hpve99q8p {
  d: path("M12 6c-2-1.75-7.5-1.5-7.5 4c0 4 3 6.5 5 6.5c1 0 1.5-.5 2.5-.5s1.5.5 2.5.5c2 0 5-2.5 5-6.5c0-5.5-5.5-5.75-7.5-4Zm0 10v5.5");
}

.qj1lnacwz {
  d: path("M7.75 10.5a4 4 0 0 1 2-3M12 6c0-1.5 1-3 2.75-3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
