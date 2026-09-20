<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k3hxzxbpv"/><path class="rsejymb4c"/><path class="uom89l0gh"/><path class="d3t8z9b-e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:bedtime-story-duotone-thin" /></template>
<style>
.d3t8z9b-e {
  d: path("M14 2a5 5 0 1 0 0 10 4 4 0 0 1 0 -10");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k3hxzxbpv {
  fill: currentColor;
  d: path("M14 2a5 5 0 1 0 0 10 4 4 0 0 1 0 -10");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.rsejymb4c {
  d: path("M12 13q-3 -3 -9 -3v10c4 0 7 1 9 2");
}

.uom89l0gh {
  d: path("M12 13q3 -3 9 -3v10c-4 0 -7 1 -9 2");
}

</style>
