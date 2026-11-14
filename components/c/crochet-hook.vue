<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fax97c93b"/><path class="add51x2-p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:crochet-hook" /></template>
<style>
.add51x2-p {
  d: path("M14 16.5c2.5.5 4 2.25 4.5 4.75");
}

.fax97c93b {
  d: path("m3.818 17.707l3.889-3.889a1.75 1.75 0 0 1 2.475 0a1.75 1.75 0 0 1 0 2.475l-3.889 3.889a1.75 1.75 0 0 1-2.475 0a1.75 1.75 0 0 1 0-2.475m6.432-3.957L19 5c.75-.75 2-.25 1.75 1M13.5 18a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
