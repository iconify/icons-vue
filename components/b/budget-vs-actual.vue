<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v_ui7pbkk"/><path class="nni9dsbsv"/><path class="pm9zeib8v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:budget-vs-actual" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nni9dsbsv {
  fill: currentColor;
  d: path("M7.75 21v-9h2.75v9Zm11 0V7h2.75v14Z");
}

.pm9zeib8v {
  d: path("M2.5 14.5V9.75A.75.75 0 0 1 3.25 9H4.5a.75.75 0 0 1 .75.75v4.75M2.5 17v4m2.75-4v4m8.25-10V4.75a.75.75 0 0 1 .75-.75h1.25a.75.75 0 0 1 .75.75V11m-2.75 2.5V21m2.75-7.5V21");
}

.v_ui7pbkk {
  d: path("M2.5 21h19");
}

</style>
