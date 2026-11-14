<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ta9xehbwj"/><path class="oij1-7y-i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:charger-highway" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oij1-7y-i {
  d: path("m7.5 6l-2 3.5H8l-1.5 3m7 9L16.75 3m4.75 18.5L19.75 3M17.5 20.5l.25-4m0-3L18 10");
}

.ta9xehbwj {
  d: path("M5.125 3h2.75A2.625 2.625 0 0 1 10.5 5.625v13.25A2.625 2.625 0 0 1 7.875 21.5h-2.75A2.625 2.625 0 0 1 2.5 18.875V5.625A2.625 2.625 0 0 1 5.125 3");
}

</style>
