<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="loeu81btj"/><path class="uc4ot1bkm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:loan-recovery" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.loeu81btj {
  d: path("M6 2.5h12m-6 0v3m0 0V8a1.75 1.75 0 0 1-3.5 0m-1.25 8.75a4.75 4.75 0 1 0 9.5 0a4.75 4.75 0 1 0-9.5 0");
}

.uc4ot1bkm {
  d: path("M13.5 15.25q-.375-.75-1.5-.75c-.75 0-1.5.25-1.5 1c0 1.25 3 .75 3 2.5c0 .5-.75 1-1.5 1q-1.125 0-1.5-.75M12 13.5v1m0 4.5v1");
}

</style>
