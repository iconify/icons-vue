<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t6kisabuh"/><path class="aj1uncbqw"/><path class="y4-ssjnrw"/><path class="om9c7ck0x"/><path class="osdsz4bam"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:degree-fahrenheit-duotone-thin" /></template>
<style>
.aj1uncbqw {
  d: path("M4 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.om9c7ck0x {
  d: path("M13 8h7");
}

.osdsz4bam {
  d: path("M13 14h5");
}

.t6kisabuh {
  fill: currentColor;
  d: path("M4 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.y4-ssjnrw {
  d: path("M13 8v12");
}

</style>
