<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="vf785v0lm"/><path class="xl00inbad"/><path class="em-7wkv2l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:feature-phone-sharp" /></template>
<style>
.em-7wkv2l {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 14h.01M12 14h.01M15 14h.01M9 17.5h.01m2.99 0h.01m2.99 0h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.vf785v0lm {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 2.75h11.5v18.5H6.25z");
}

.xl00inbad {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 5.5h5.5v5h-6.5v-5z");
}

</style>
