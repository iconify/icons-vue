<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t6klew5pq"/><path class="rtzcjpz7f"/><path class="pq65d4pux"/><path class="wuavqcbqp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:corner-up-left-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pq65d4pux {
  d: path("M20 20V10H4");
}

.rtzcjpz7f {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 5 -5 5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.t6klew5pq {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M20 20V10H4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wuavqcbqp {
  d: path("m9 5 -5 5 5 5");
}

</style>
