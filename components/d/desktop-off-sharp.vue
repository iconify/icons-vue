<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ww4t9bb-h"/><path class="p_gnhwivz"/><path class="uca16cvvx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:desktop-off-sharp" /></template>
<style>
.p_gnhwivz {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.5 16.75h.01");
}

.uca16cvvx {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.75 7.25h1.5");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.ww4t9bb-h {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 4.75h10.5v9.5H2.75zM8 14.25v4.5m-2.5 0h5m5.25-15h5.5v16.5h-5.5z");
}

</style>
