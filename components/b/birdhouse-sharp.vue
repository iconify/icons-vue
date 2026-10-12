<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="u4-b69bod"/><path class="lp1eksghb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:birdhouse-sharp" /></template>
<style>
.lp1eksghb {
  d: path("M10 12.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0M12 18v3.25");
}

.u4-b69bod {
  d: path("m12.77 3.39l5.96 4.97l.77.64h-15l.77-.64l5.96-4.97l.77-.64zM6.25 9h11.5v9H6.25z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
