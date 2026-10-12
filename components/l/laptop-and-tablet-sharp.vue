<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="apgf9mbmn"/><path class="rsrzh5byz"/><path class="hfwhd-zqz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:laptop-and-tablet-sharp" /></template>
<style>
.apgf9mbmn {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 3.75h14v3.5h-9v7.5h-7v-11zm-3 14.5h7.75");
}

.hfwhd-zqz {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.5 18.5h.01");
}

.rsrzh5byz {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.75 10.25h7.5v11h-7.5z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
