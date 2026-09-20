<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nrlkc9bnf"/><path class="gswqrzb0v"/><path class="n1soxcq3c"/><path class="vzyxlnb8e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:baby-outline-thin" /></template>
<style>
.gswqrzb0v {
  d: path("M12 4c3 0 3 3 0 3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n1soxcq3c {
  d: path("M8 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.nrlkc9bnf {
  d: path("M4 12a8 8 0 1 0 16 0 8 8 0 1 0 -16 0");
}

.vzyxlnb8e {
  d: path("M14 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
