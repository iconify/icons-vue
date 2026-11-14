<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="om9mknbjc"/><path class="rf3v3oblj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fall-arrest-harness" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.om9mknbjc {
  d: path("m6.5 2.5l3 4.5m8-4.5l-3 4.5m-5 0h5v1.5a2.5 2.5 0 0 1-5 0Z");
}

.rf3v3oblj {
  d: path("M9.75 9.75L6.5 15v6.5m7.75-11.75L17.5 15v6.5M3.5 15h17");
}

</style>
