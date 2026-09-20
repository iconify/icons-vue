<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nrlkc9bnf"/><path class="ei_3wdi5i"/><path class="ymfnpaceh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:globe-spin-outline-thin" /></template>
<style>
.ei_3wdi5i {
  d: path("M12 20a8 8 0 0 1 0 -16");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nrlkc9bnf {
  d: path("M4 12a8 8 0 1 0 16 0 8 8 0 1 0 -16 0");
}

.ymfnpaceh {
  d: path("m12 2 2.5 2.5L12 7");
}

</style>
