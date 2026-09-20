<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wzrnw0b2n"/><path class="a5tuk3h7e"/><path class="rknj6qbnf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:artifact-retention-outline-thin" /></template>
<style>
.a5tuk3h7e {
  d: path("M4 10h16");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rknj6qbnf {
  d: path("M10 13h4l-4 4h4Z");
}

.wzrnw0b2n {
  d: path("M14 6h3a3 3 0 0 1 3 3v8a3 3 0 0 1 -3 3H7a3 3 0 0 1 -3 -3V9a3 3 0 0 1 3 -3h3");
}

</style>
