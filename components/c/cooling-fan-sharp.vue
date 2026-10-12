<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="itxcm0bbl"/><path class="eyan5kb3w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cooling-fan-sharp" /></template>
<style>
.eyan5kb3w {
  d: path("m12.45 10.83l1.52-3.97l.44-1.16l.98.78l1.26 1.01l.98.78l-1.05.69l-3.54 2.35L12 12zm.72 1.62l3.97 1.52l1.16.44l-.78.98l-1.01 1.26l-.78.98l-.69-1.05l-2.35-3.54L12 12zm-1.62.72l-1.52 3.97l-.44 1.16l-.98-.78l-1.26-1.01l-.98-.78l1.05-.69l3.54-2.35L12 12zm-.72-1.62l-3.97-1.52l-1.16-.44l.78-.98l1.01-1.26l.78-.98l.69 1.05l2.35 3.54L12 12z");
}

.itxcm0bbl {
  d: path("M2.75 2.75h18.5v18.5H2.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
