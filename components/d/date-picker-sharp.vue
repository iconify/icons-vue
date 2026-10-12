<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="waa338bte"/><path class="h6wfn2b6s"/><path class="yz_y5kbth"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:date-picker-sharp" /></template>
<style>
.h6wfn2b6s {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.75 14h.01M11 14h.01m-3.26 3.25h.01");
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

.yz_y5kbth {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m14.95 14.51l5.35 1.98l.7.26l-.72.22l-1.81.56l-.72.22l-.22.72l-.56 1.81l-.22.72l-.26-.7l-1.98-5.35l-.26-.7z");
}

</style>
