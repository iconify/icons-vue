<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="np6j5-bet"/><path class="hpi-asn8f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:first-place-ribbon" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hpi-asn8f {
  d: path("M8.75 14.75L7.5 21.5l4.5-2.25l4.5 2.25l-1.25-6.75M10.75 8l1.5-1.25v5.5");
}

.np6j5-bet {
  d: path("m12.744 3.223l.144.139a1.5 1.5 0 0 0 1.412.379l.194-.049a1.07 1.07 0 0 1 1.289.744l.054.192a1.5 1.5 0 0 0 1.035 1.035l.192.054a1.07 1.07 0 0 1 .744 1.289l-.049.194a1.5 1.5 0 0 0 .379 1.412l.139.144a1.07 1.07 0 0 1 0 1.488l-.139.144a1.5 1.5 0 0 0-.379 1.412l.049.194a1.07 1.07 0 0 1-.744 1.289l-.192.054a1.5 1.5 0 0 0-1.035 1.035l-.054.192a1.07 1.07 0 0 1-1.289.744l-.194-.049a1.5 1.5 0 0 0-1.412.379l-.144.139a1.07 1.07 0 0 1-1.488 0l-.144-.139a1.5 1.5 0 0 0-1.412-.379l-.194.049a1.07 1.07 0 0 1-1.289-.744l-.054-.192a1.5 1.5 0 0 0-1.035-1.035l-.192-.054a1.07 1.07 0 0 1-.744-1.289l.049-.194a1.5 1.5 0 0 0-.379-1.412l-.139-.144a1.07 1.07 0 0 1 0-1.488l.139-.144A1.5 1.5 0 0 0 6.241 7.2l-.049-.194a1.07 1.07 0 0 1 .744-1.289l.192-.054a1.5 1.5 0 0 0 1.035-1.035l.054-.192a1.07 1.07 0 0 1 1.289-.744l.194.049a1.5 1.5 0 0 0 1.412-.379l.144-.139a1.07 1.07 0 0 1 1.488 0");
}

</style>
