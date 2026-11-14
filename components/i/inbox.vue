<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zf3fapbaj"/><path class="p2wn83b4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:inbox" /></template>
<style>
.p2wn83b4s {
  d: path("M3 12.5h5L9.5 15h5l1.5-2.5h5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zf3fapbaj {
  d: path("M5.5 4.5h13l2.5 8v7H3v-7Z");
}

</style>
