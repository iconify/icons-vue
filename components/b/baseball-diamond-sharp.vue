<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="g_d20qbbb"/><path class="to8m3ibcr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:baseball-diamond-sharp" /></template>
<style>
.g_d20qbbb {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.75 6.25l4 4m0 3.5l-4 4m-3.5 0l-4-4m0-3.5l4-4m2.03-2.97l.94.94l.28.28l-.28.28l-.94.94L12 6l-.28-.28l-.94-.94l-.28-.28l.28-.28l.94-.94L12 3zm7.5 7.5l.94.94l.28.28l-.28.28l-.94.94l-.28.28l-.28-.28l-.94-.94L18 12l.28-.28l.94-.94l.28-.28zm-15 0l.94.94L6 12l-.28.28l-.94.94l-.28.28l-.28-.28l-.94-.94L3 12l.28-.28l.94-.94l.28-.28zm7.55 7.95l1.09.79l.33.23v1.5h-3.5v-1.5l.33-.23l1.09-.79l.33-.23z");
}

.to8m3ibcr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
