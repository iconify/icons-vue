<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ytfifl95c"/><path class="q63y-pbsz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:finger-paint-sharp" /></template>
<style>
.q63y-pbsz {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 9.25V7.5m3 1.25v-4m3 4V4m3 5.25V6m3.25 9.25l.75-2.75");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.ytfifl95c {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 11.5h11v9.75h-11z");
}

</style>
