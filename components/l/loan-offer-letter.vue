<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fbf28eboe"/><path class="lpmq4tukk"/><path class="ws3itabvw"/><path class="z6gbq4bst"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:loan-offer-letter" /></template>
<style>
.fbf28eboe {
  d: path("M2.5 12v7.5a2 2 0 0 0 2 2h15a2 2 0 0 0 2-2V12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lpmq4tukk {
  d: path("m2.5 12l9.5 5.5l9.5-5.5M5 11.5V4a1.5 1.5 0 0 1 1.5-1.5h11A1.5 1.5 0 0 1 19 4v7.5");
}

.ws3itabvw {
  d: path("M8.75 7.75a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0");
}

.z6gbq4bst {
  d: path("M13 6.75c-.25-.5-.5-.5-1-.5S11 6.5 11 7c0 .75 2 .5 2 1.5c0 .5-.5.75-1 .75s-1 0-1-.5m1-3.25v.75m0 3V10");
}

</style>
