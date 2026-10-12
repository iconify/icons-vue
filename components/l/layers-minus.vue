<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rtfex0bei"/><path class="jho2glbuy"/><path class="ewaodbbhs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:layers-minus" /></template>
<style>
.ewaodbbhs {
  d: path("M2.75 16.5L12 21.25l9.25-4.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jho2glbuy {
  d: path("M2.75 12L12 16.75L21.25 12");
}

.rtfex0bei {
  d: path("m13.11 3.32l7.03 3.61q1.11.57 0 1.14l-7.03 3.61q-1.11.57-2.22 0L3.86 8.07q-1.11-.57 0-1.14l7.03-3.61q1.11-.57 2.22 0");
}

</style>
