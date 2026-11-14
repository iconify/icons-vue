<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mnkn37bqy"/><path class="fa7xchh_g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:audit-trail-medical" /></template>
<style>
.fa7xchh_g {
  fill: currentColor;
  d: path("M17 18a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

.mnkn37bqy {
  d: path("M11.6 19H3V2.5h13v10.3M6 7h7m-7 3.5h7M6 14h4.5m3.75 4c1.25-2 2.5-2.75 3.75-2.75s2.5.75 3.75 2.75c-1.25 2-2.5 2.75-3.75 2.75S15.5 20 14.25 18Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
