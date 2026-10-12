<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="waa338bte"/><path class="ncq0ct0me"/><path class="am08eabyg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:calendar-export-sharp" /></template>
<style>
.am08eabyg {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m14.75 14.75l5.5 5.5m0-3.5v3.5h-3.5");
}

.ncq0ct0me {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 14h.01m3.24 0h.01M8 17.25h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.waa338bte {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.75 20.25h-8v-15h16.5v6.5M3.75 10h16.5M8 2.75v4.5m8-4.5v4.5");
}

</style>
