<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="z7k3ah_pl"/><path class="ktc02ox-l"/><path class="ack-1vw1a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:door-lock-sharp" /></template>
<style>
.ack-1vw1a {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.75 13.5h6.5v7.75h-6.5zm1.75 0v-3h3v3");
}

.ktc02ox-l {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.75 12h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.z7k3ah_pl {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h9.5v18.5h-9.5z");
}

</style>
