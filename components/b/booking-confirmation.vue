<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k513vsjuz"/><path class="hfebp-bde"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:booking-confirmation" /></template>
<style>
.hfebp-bde {
  d: path("m9.25 6.5l2 2L15 4.75M8.5 12h1.25m1.65 0h1.25m1.6 0h1.25m-7 4.5h7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k513vsjuz {
  d: path("M4.75 4.75a2 2 0 0 1 2-2h10.5a2 2 0 0 1 2 2v5a2.25 2.25 0 0 0 0 4.5v5a2 2 0 0 1-2 2H6.75a2 2 0 0 1-2-2v-5a2.25 2.25 0 0 0 0-4.5Z");
}

</style>
