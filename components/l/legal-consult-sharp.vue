<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="cax_t3h4g"/><path class="oyv17kw6x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:legal-consult-sharp" /></template>
<style>
.cax_t3h4g {
  d: path("M4.75 2.75h16.5v15H11l-4.25 3.5v-3.5h-4v-15z");
}

.oyv17kw6x {
  d: path("m13.75 6.25l-.538-1H10.25v1.4c0 1.95 3.5 1.75 3.5 3.7m-3.5 3.4l.538 1h2.962v-1.4c0-1.95-3.5-1.75-3.5-3.7");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
