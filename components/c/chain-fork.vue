<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mhtuhqc2j"/><path class="w5zu1lbnb"/><path class="ggznlfbws"/><path class="h9uy-z23d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chain-fork" /></template>
<style>
.ggznlfbws {
  d: path("m2 4.5l3.5 2l3.5-2m-3.5 2v4m13.744-7.575l2 1.143A1.5 1.5 0 0 1 22 5.37v2.26a1.5 1.5 0 0 1-.756 1.302l-2 1.143a1.5 1.5 0 0 1-1.488 0l-2-1.143A1.5 1.5 0 0 1 15 7.63V5.37a1.5 1.5 0 0 1 .756-1.302l2-1.143a1.5 1.5 0 0 1 1.488 0");
}

.h9uy-z23d {
  d: path("m15 4.5l3.5 2l3.5-2m-3.5 2v4m-13 0l6.5 3l6.5-3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mhtuhqc2j {
  d: path("m12.744 13.925l2 1.143a1.5 1.5 0 0 1 .756 1.302v2.26a1.5 1.5 0 0 1-.756 1.302l-2 1.143a1.5 1.5 0 0 1-1.488 0l-2-1.143A1.5 1.5 0 0 1 8.5 18.63v-2.26a1.5 1.5 0 0 1 .756-1.302l2-1.143a1.5 1.5 0 0 1 1.488 0");
}

.w5zu1lbnb {
  d: path("m8.5 15.5l3.5 2l3.5-2m-3.5 2v4M6.244 2.925l2 1.143A1.5 1.5 0 0 1 9 5.37v2.26a1.5 1.5 0 0 1-.756 1.302l-2 1.143a1.5 1.5 0 0 1-1.488 0l-2-1.143A1.5 1.5 0 0 1 2 7.63V5.37a1.5 1.5 0 0 1 .756-1.302l2-1.143a1.5 1.5 0 0 1 1.488 0");
}

</style>
