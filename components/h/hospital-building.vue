<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="aibe9_5oq"/><path class="ul5ld_3si"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hospital-building" /></template>
<style>
.aibe9_5oq {
  d: path("M10.625 2.5h2.75A2.625 2.625 0 0 1 16 5.125v13.75a2.625 2.625 0 0 1-2.625 2.625h-2.75A2.625 2.625 0 0 1 8 18.875V5.125A2.625 2.625 0 0 1 10.625 2.5M8 9H4c-.8 0-1.5.7-1.5 1.5v11H8M16 9h4c.8 0 1.5.7 1.5 1.5v11H16m-5.75-16v6m3.5-6v6m-3.5-3h3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ul5ld_3si {
  d: path("M10.5 21.5v-4h3v4m-8.25-8h.01m13.49 0h.01");
}

</style>
