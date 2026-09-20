<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="niggb1byh"/><path class="gdju1xbel"/><path class="wzhctub5z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:magnetic-field-outline-thin" /></template>
<style>
.gdju1xbel {
  d: path("M3 13c0 -9 18 -9 18 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.niggb1byh {
  d: path("M8 10h8v4H8Z");
}

.wzhctub5z {
  d: path("M3 11c0 9 18 9 18 0");
}

</style>
