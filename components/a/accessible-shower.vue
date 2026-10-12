<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vlpz9peuq"/><path class="c57dijbcm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:accessible-shower" /></template>
<style>
.c57dijbcm {
  d: path("M9.5 9.5a3.75 3.75 0 0 1 7.5 0Zm.25 3V14m3.5-1.5V14m3.5-1.5V14");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vlpz9peuq {
  d: path("M4.75 21.25v-16a2.5 2.5 0 0 1 2.5-2.5h3.5a2.5 2.5 0 0 1 2.5 2.5v.5");
}

</style>
