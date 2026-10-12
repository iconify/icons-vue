<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="agyx3ab2i"/><path class="exj_d774i"/><path class="f0cu2pb0t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:agent-swarm-sharp" /></template>
<style>
.agyx3ab2i {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h6v6h-6zm12.5 0h6v6h-6zm-12.5 12.5h6v6h-6zm12.5 0h6v6h-6z");
}

.exj_d774i {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.75 5.75h.01m12.49 0h.01M5.75 18.25h.01m12.49 0h.01");
}

.f0cu2pb0t {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 8.5q.42 3.08 3.5 3.5q-3.08.42-3.5 3.5q-.42-3.08-3.5-3.5q3.08-.42 3.5-3.5Z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
