<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zf7mx_7mn"/><path class="ufignx6hm"/><path class="cy34vrbps"/><path class="ooykrqbbx"/><path class="t3p_xpene"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:bucket-data-outline-thin" /></template>
<style>
.cy34vrbps {
  d: path("M10 8.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ooykrqbbx {
  d: path("M3 13v7h7v-7");
}

.t3p_xpene {
  d: path("M14 13v7h7v-7");
}

.ufignx6hm {
  d: path("M15.5 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.zf7mx_7mn {
  d: path("M4.5 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
