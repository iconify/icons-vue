<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eq8p65fcb"/><path class="sxlwlmkmh"/><path class="r7xk8o29f"/><path class="sjot3p-qh"/><path class="n_pijqp-h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:crossword-outline-thin" /></template>
<style>
.eq8p65fcb {
  d: path("M4 4v16h16V4Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n_pijqp-h {
  d: path("M14 16h4");
}

.r7xk8o29f {
  d: path("M12 4v16");
}

.sjot3p-qh {
  d: path("M6 8h4");
}

.sxlwlmkmh {
  d: path("M4 12h16");
}

</style>
