<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oy9aotbsd"/><path class="v13epqbii"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:compass" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oy9aotbsd {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0");
}

.v13epqbii {
  d: path("m14.5 11l-.761 1.903a1.5 1.5 0 0 1-.836.836L11 14.5A1.154 1.154 0 0 1 9.5 13l.761-1.903a1.5 1.5 0 0 1 .836-.836L13 9.5a1.154 1.154 0 0 1 1.5 1.5");
}

</style>
