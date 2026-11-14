<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e3gnpsb6o"/><path class="z6oj9tbnv"/><path class="o__qy7e_o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:clothing-return" /></template>
<style>
.e3gnpsb6o {
  d: path("M20 13.524V5.5l-4.5-2C15 5.25 13.75 6.25 12 6.25s-3-1-3.5-2.75L4 5.5v14h10.576M7.5 8.5v11m9-11v2.1");
}

.o__qy7e_o {
  d: path("M16.75 14.25L15 16l1.75 1.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z6oj9tbnv {
  d: path("M20.5 20.5v-2A2.5 2.5 0 0 0 18 16h-3");
}

</style>
