<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tllw2iado"/><path class="mukpw2btv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:arch-trefoil" /></template>
<style>
.mukpw2btv {
  d: path("M9.75 9.5a2.5 2.5 0 1 1 4.5 0A2.5 2.5 0 1 1 12 13.25A2.5 2.5 0 1 1 9.75 9.5Z");
}

.tllw2iado {
  d: path("M4.5 21.5v-11a7.5 7.5 0 0 1 15 0v11M3 21.5h18");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
