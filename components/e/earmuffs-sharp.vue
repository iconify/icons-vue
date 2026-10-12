<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="hf6wknrvt"/><path class="aqp_8oaft"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:earmuffs-sharp" /></template>
<style>
.aqp_8oaft {
  d: path("M9 18a1.1 1.1 0 0 1-1.5 1.5l-1 2.182l-1-2.182A1.1 1.1 0 0 1 4 18l-2.182-1L4 16a1.1 1.1 0 0 1 1.5-1.5l1-2.182l1 2.182A1.1 1.1 0 0 1 9 16l2.182 1zm11 0a1.1 1.1 0 0 1-1.5 1.5l-1 2.182l-1-2.182A1.1 1.1 0 0 1 15 18l-2.182-1L15 16a1.1 1.1 0 0 1 1.5-1.5l1-2.182l1 2.182A1.1 1.1 0 0 1 20 16l2.182 1z");
}

.hf6wknrvt {
  d: path("M6.5 13.5C6.5 7.75 9 4.25 12 4.25s5.5 3.5 5.5 9.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
