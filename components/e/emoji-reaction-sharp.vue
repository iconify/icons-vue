<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="lcq208b8a"/><circle class="gqdwd_bjh"/><path class="bd11gtbhg"/><path class="zni505jlj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:emoji-reaction-sharp" /></template>
<style>
.bd11gtbhg {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.25 15.25h.01m1.99 0h.01");
}

.gqdwd_bjh {
  cx: 17.25px;
  cy: 17.25px;
  r: 4px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lcq208b8a {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 3.25h11v11h-7L5.65 17l-1.15.92v-3.67l-1.838-.576l.088-1.924v-8.5z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.zni505jlj {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m16 17.75l1.25 1.206l1.25-1.206");
}

</style>
