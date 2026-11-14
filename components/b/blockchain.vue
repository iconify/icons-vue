<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uqd2xobim"/><path class="yem5rlizq"/><path class="p7qv1ibpj"/><path class="wahc4hz1p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:blockchain" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p7qv1ibpj {
  d: path("m2.5 15.5l3.5 2l3.5-2m-3.5 2v4m12.744-7.575l2 1.143a1.5 1.5 0 0 1 .756 1.302v2.26a1.5 1.5 0 0 1-.756 1.302l-2 1.143a1.5 1.5 0 0 1-1.488 0l-2-1.143a1.5 1.5 0 0 1-.756-1.302v-2.26a1.5 1.5 0 0 1 .756-1.302l2-1.143a1.5 1.5 0 0 1 1.488 0");
}

.uqd2xobim {
  d: path("m12.744 2.425l2 1.143A1.5 1.5 0 0 1 15.5 4.87v2.26a1.5 1.5 0 0 1-.756 1.302l-2 1.143a1.5 1.5 0 0 1-1.488 0l-2-1.143A1.5 1.5 0 0 1 8.5 7.13V4.87a1.5 1.5 0 0 1 .756-1.302l2-1.143a1.5 1.5 0 0 1 1.488 0");
}

.wahc4hz1p {
  d: path("m14.5 15.5l3.5 2l3.5-2m-3.5 2v4M8.5 8L6 13.5M15.5 8l2.5 5.5m-8.5 4h5");
}

.yem5rlizq {
  d: path("M8.5 4L12 6l3.5-2M12 6v4m-5.256 3.925l2 1.143A1.5 1.5 0 0 1 9.5 16.37v2.26a1.5 1.5 0 0 1-.756 1.302l-2 1.143a1.5 1.5 0 0 1-1.488 0l-2-1.143A1.5 1.5 0 0 1 2.5 18.63v-2.26a1.5 1.5 0 0 1 .756-1.302l2-1.143a1.5 1.5 0 0 1 1.488 0");
}

</style>
