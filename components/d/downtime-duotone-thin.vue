<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dv7-1kb6f"/><path class="hen7e0d7r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:downtime-duotone-thin" /></template>
<style>
.dv7-1kb6f {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 12h4V6h4v12h4v-6h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hen7e0d7r {
  d: path("M3 12h4V6h4v12h4v-6h6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
