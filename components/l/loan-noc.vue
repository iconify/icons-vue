<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vd_9j0p8a"/><path class="av65z056k"/><path class="qi2xwumym"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:loan-noc" /></template>
<style>
.av65z056k {
  d: path("m16.5 12l.841.861l1.159-.325l.298 1.166l1.166.298l-.325 1.159l.861.841l-.861.841l.325 1.159l-1.166.298l-.298 1.166l-1.159-.325L16.5 20l-.841-.861l-1.159.325l-.298-1.166L13.036 18l.325-1.159L12.5 16l.861-.841L13.036 14l1.166-.298l.298-1.166l1.159.325Z");
}

.qi2xwumym {
  d: path("M14.75 16L16 17.25l2.25-2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vd_9j0p8a {
  d: path("M9.5 17h-7V4h19v7.5M6 8h9m-9 3.5h4.5");
}

</style>
