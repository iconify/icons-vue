<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="h2pe88b7k"/><path class="zw9ztthdt"/><path class="ppp2pccnu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:badger-sharp" /></template>
<style>
.h2pe88b7k {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 9.25v-2L5.75 6L5.6 4.5l-.119-1.313L6.55 3.9L8 4.9c1.25-.3 2.6-.4 4-.4s2.75.1 4 .4l1.45-1l1.069-.713L18.4 4.5L18.25 6l1.25 1.25v3.833l-1.25 1.667l-4.75 6.5l-1.5 2l-1.5-2l-4.75-6.5l-1.25-1.667z");
}

.ppp2pccnu {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 10.25h.01m9.99 0h.01m-5.01 7h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.zw9ztthdt {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 14.5C10 11.5 9.25 8 8.75 5m4.75 9.5c.5-3 1.25-6.5 1.75-9.5");
}

</style>
