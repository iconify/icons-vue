<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="td9f6wbon"/><path class="ih_hzbmoj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:inventory-count-duotone-bold" /></template>
<style>
.ih_hzbmoj {
  d: path("M4 20v-8h16v8Zm8 -8v8m-4 -8V4h8v8");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.td9f6wbon {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 20v-8h16v8Zm8 -8v8m-4 -8V4h8v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
