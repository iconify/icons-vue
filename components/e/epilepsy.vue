<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f2kulnbzp"/><path class="vid1lbbyy"/><path class="ib2j964_g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:epilepsy" /></template>
<style>
.f2kulnbzp {
  d: path("M7 5.75c.5-2 2.75-3 4.75-2.25c1.25-1.25 4-1 5 .5c2.25 0 3.75 1.75 3.5 3.75c1.5 1.25 1.5 3.75.25 5c.25 2.25-1.5 3.75-3.5 3.5c-1 1.5-3.5 2-5 1c-1.75 1-4.25.5-5-1c-2.25.25-4-1.5-3.5-3.5C2.25 11.5 2.25 9 3.75 8c0-1.75 1.5-2.75 3.25-2.25m7.75 12l.75 3.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ib2j964_g {
  d: path("m6 9l1.5 1m10 3.5l1.25 1");
}

.vid1lbbyy {
  fill: currentColor;
  d: path("m12.908 5.523l-3.087 4.722A.811.811 0 0 0 10.5 11.5a1.1 1.1 0 0 1 1.048 1.43l-.298.945a.44.44 0 0 0 .769.401l2.643-3.436a.677.677 0 0 0-.537-1.09a.96.96 0 0 1-.9-1.29l1.059-2.874A.436.436 0 0 0 13.875 5a1.16 1.16 0 0 0-.967.523");
}

</style>
