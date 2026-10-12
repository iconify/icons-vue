<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ifob98x5h"/><path class="g6o7hcb4b"/><path class="xjhwurbhd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chat-image-sharp" /></template>
<style>
.g6o7hcb4b {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.75 14.25l3.5-3.75L13 13.25l1.75-1.75l2.5 2.5");
}

.ifob98x5h {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 6.25v-2.5h18.5v14H12.5L8 20.85l-1.25 1v-4.1h-4v-2.5Z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.xjhwurbhd {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.25 7.5h.01");
}

</style>
