<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ac91ayw-i"/><path class="ixya1fhml"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:last-mile" /></template>
<style>
.ac91ayw-i {
  d: path("m13.472 14.556l2.75-2.588a1.5 1.5 0 0 1 2.056 0l2.75 2.588a1.5 1.5 0 0 1 .472 1.092V20a1.5 1.5 0 0 1-1.5 1.5h-5.5A1.5 1.5 0 0 1 13 20v-4.352a1.5 1.5 0 0 1 .472-1.092");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ixya1fhml {
  d: path("M15.75 21.5V18h3v3.5m-1.5-13.25s-2.5-1.75-2.5-3.75a2.5 2.5 0 0 1 5 0c0 2-2.5 3.75-2.5 3.75M2.5 21.5h3m2.75 0h2");
}

</style>
