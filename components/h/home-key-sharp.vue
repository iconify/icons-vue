<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="gwyoxnosv"/><path class="emkob7bel"/><path class="af11bwb4u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:home-key-sharp" /></template>
<style>
.af11bwb4u {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.75 12.5l9.75-9.75m-2 2l2 2m-4.5.5l2 2");
}

.emkob7bel {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 16.25h.01");
}

.gwyoxnosv {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.96 11.54l2.33 1.92l.96.79v6h-8.5v-6l.96-.79l2.33-1.92l.96-.79z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
