<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uiwg65buh"/><path class="iw2rschqa"/><path class="nf4wfrbrg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:battery-recycling" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iw2rschqa {
  d: path("M8.922 20.457A9 9 0 0 1 7.5 4.206M17 6.75l2.75.75l.75-2.75");
}

.nf4wfrbrg {
  d: path("M15.078 3.543A9 9 0 0 1 16.5 19.794M7 17.25l-2.75-.75l-.75 2.75");
}

.uiwg65buh {
  d: path("M9.625 9.25h3.25a2.625 2.625 0 0 1 2.625 2.625v.25a2.625 2.625 0 0 1-2.625 2.625h-3.25A2.625 2.625 0 0 1 7 12.125v-.25A2.625 2.625 0 0 1 9.625 9.25M18.25 11v2");
}

</style>
