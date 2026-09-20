<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mg7aqnbsf"/><path class="rtofn9dtv"/><path class="b26q0zi5z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:align-start-horizontal-outline-thin" /></template>
<style>
.b26q0zi5z {
  d: path("M14 7h4v6h-4Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mg7aqnbsf {
  d: path("M3 4h18");
}

.rtofn9dtv {
  d: path("M7 7h4v10H7Z");
}

</style>
