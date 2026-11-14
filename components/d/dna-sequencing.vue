<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a33g0q45s"/><path class="yar5v2bdf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dna-sequencing" /></template>
<style>
.a33g0q45s {
  d: path("M4.5 2.5c0 4.5 8 5 8 9.5s-8 5-8 9.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yar5v2bdf {
  d: path("M12.5 2.5c0 4.5-8 5-8 9.5s8 5 8 9.5m-8-9.5h8m2.75 5.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m4 1.75L21 21");
}

</style>
