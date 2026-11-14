<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ecc-66ukw"/><path class="q-mlfdbyt"/><path class="ato3-mb3a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hotel-porter" /></template>
<style>
.ato3-mb3a {
  d: path("M6.25 19.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m8.5 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

.ecc-66ukw {
  d: path("M4.5 3v15h15");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q-mlfdbyt {
  d: path("M9.25 12h7.5a1.75 1.75 0 0 1 1.75 1.75v2.5A1.75 1.75 0 0 1 16.75 18h-7.5a1.75 1.75 0 0 1-1.75-1.75v-2.5A1.75 1.75 0 0 1 9.25 12m1.5-6h4.5A1.75 1.75 0 0 1 17 7.75v2.5A1.75 1.75 0 0 1 15.25 12h-4.5A1.75 1.75 0 0 1 9 10.25v-2.5A1.75 1.75 0 0 1 10.75 6");
}

</style>
