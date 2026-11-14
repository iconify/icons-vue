<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r7uvj1wzb"/><path class="n0v68cbqh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:automation-condition" /></template>
<style>
.n0v68cbqh {
  d: path("M10 10a2 2 0 1 1 2 2v1m0 2.75h.01");
}

.r7uvj1wzb {
  d: path("m10 6.25l.25-3h3.5l.25 3l1.75 1.25l3-1.5l1.75 3.25L18 11v2l2.5 1.75L18.75 18l-3-1.5L14 17.75l-.25 3h-3.5l-.25-3l-1.75-1.25l-3 1.5l-1.75-3.25L6 13v-2L3.5 9.25L5.25 6l3 1.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
