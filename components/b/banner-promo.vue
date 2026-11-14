<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="carintbwr"/><path class="oys748t3w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:banner-promo" /></template>
<style>
.carintbwr {
  d: path("M6.875 5.5h10.25A4.375 4.375 0 0 1 21.5 9.875v4.25a4.375 4.375 0 0 1-4.375 4.375H6.875A4.375 4.375 0 0 1 2.5 14.125v-4.25A4.375 4.375 0 0 1 6.875 5.5M15 10h3.75M15 14h3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oys748t3w {
  d: path("m9.25 9.5l.123.307a1.5 1.5 0 0 0 1.393.943H11a.47.47 0 0 1 .309.823l-.333.291a1.5 1.5 0 0 0-.449 1.56l.098.326a.47.47 0 0 1-.711.526l-.332-.221a1.5 1.5 0 0 0-1.664 0l-.332.221a.47.47 0 0 1-.711-.526l.098-.326a1.5 1.5 0 0 0-.449-1.56l-.333-.291a.47.47 0 0 1 .309-.823h.234a1.5 1.5 0 0 0 1.393-.943L8.25 9.5a.539.539 0 0 1 1 0");
}

</style>
