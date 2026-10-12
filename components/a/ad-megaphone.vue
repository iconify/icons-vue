<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t86l9bcig"/><path class="kepgnhgbs"/><rect class="kh4slxelk"/><path class="xb3xm_rdf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ad-megaphone" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kepgnhgbs {
  d: path("M5 17.75v2a1.5 1.5 0 0 0 3 0v-2m10.75-6a3.5 3.5 0 0 1 0 5");
}

.kh4slxelk {
  width: 6px;
  height: 4.5px;
  x: 15.25px;
  y: 2.75px;
  rx: 1.5px;
}

.t86l9bcig {
  d: path("M2.75 12.5a1 1 0 0 1 1-1h3.5L14.5 8a1 1 0 0 1 1.5.88v10.74a1 1 0 0 1-1.5.88L7.25 17h-3.5a1 1 0 0 1-1-1Z");
}

.xb3xm_rdf {
  d: path("m17.25 6l1-2l1 2");
}

</style>
