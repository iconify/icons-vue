<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="hmz588b6d"/><path class="wiwu8ob3f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:insurance-card-med-sharp" /></template>
<style>
.hmz588b6d {
  d: path("M2.75 5.25h18.5v13.5H2.75z");
}

.wiwu8ob3f {
  d: path("m8.25 8.25l3 1V12c0 2-1.4 3.25-3 3.75c-1.6-.5-3-1.75-3-3.75V9.25Zm0 2.25v3M6.75 12h3m3.75-2h4.75m-4.75 3h3.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
