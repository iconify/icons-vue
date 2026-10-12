<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="q1oy59b8h"/><path class="iwltsybom"/><path class="axqkcccwr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:digital-clock-sharp" /></template>
<style>
.axqkcccwr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 10.25h.01m-.01 3.5h.01");
}

.iwltsybom {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 9H9v6H5.75V9zM16 9h2.25v6H15V9z");
}

.q1oy59b8h {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 5.75h18.5v12.5H2.75z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
