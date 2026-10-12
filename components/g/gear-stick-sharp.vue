<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="lpws5cv_a"/><path class="n-rml2b7g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gear-stick-sharp" /></template>
<style>
.lpws5cv_a {
  cx: 12px;
  cy: 6.5px;
  r: 3.75px;
}

.n-rml2b7g {
  d: path("M10.75 5.25v2.5m2.5-2.5v2.5m-2.5-1.25h2.5M12 10.25v5.5m-5.12 4.57l1.49-3.64l.38-.93h6.5l.38.93l1.49 3.64l.38.93h-11z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
