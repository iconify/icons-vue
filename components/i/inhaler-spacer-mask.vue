<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wuvzo_4jj"/><path class="r96o24b3k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:inhaler-spacer-mask" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r96o24b3k {
  d: path("M16 14.25a2.75 5 0 1 0 5.5 0a2.75 5 0 1 0-5.5 0M6.25 3h1A1.75 1.75 0 0 1 9 4.75v4.5A1.75 1.75 0 0 1 7.25 11h-1A1.75 1.75 0 0 1 4.5 9.25v-4.5A1.75 1.75 0 0 1 6.25 3");
}

.wuvzo_4jj {
  d: path("M16.75 11H4.5a2 2 0 0 0-2 2v2.5a2 2 0 0 0 2 2h12.25");
}

</style>
