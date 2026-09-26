<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r63fawbfm"/><path class="vv207acuk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:app-plus-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r63fawbfm {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 2H18C20.2091 2 22 3.79086 22 6V11C22 11.5523 21.5523 12 21 12H15C13.3431 12 12 13.3431 12 15V21C12 21.5523 11.5523 22 11 22H6C3.79086 22 2 20.2091 2 18V6C2 3.79086 3.79086 2 6 2Z");
  stroke: none;
}

.vv207acuk {
  d: path("M11 21H6C4.34315 21 3 19.6569 3 18V6C3 4.34315 4.34315 3 6 3H18C19.6569 3 21 4.34315 21 6V11M18 15V21M15 18H21");
}

</style>
