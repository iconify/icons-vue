<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="emvotkb4z"/><path class="oifr9zbpt"/><path class="h4houcuor"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cosine-outline-thin" /></template>
<style>
.emvotkb4z {
  d: path("M4 20 20 4");
}

.h4houcuor {
  d: path("M4 13a7 7 0 0 1 4.95 2.05");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oifr9zbpt {
  d: path("M4 20h16");
}

</style>
