<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="wboxv9bpl"/><circle class="xs_28x-yu"/><path class="owvqk5_cl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:electric-scooter-eco-sharp" /></template>
<style>
.owvqk5_cl {
  d: path("M8.25 18.5h7.5M18 15.75l-2.25-12h2.5M8.75 14c0-3 1.75-4.75 5-4.75c0 3-1.75 4.75-5 4.75Z");
}

.wboxv9bpl {
  cx: 5.5px;
  cy: 18.5px;
  r: 2.75px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xs_28x-yu {
  cx: 18.5px;
  cy: 18.5px;
  r: 2.75px;
}

</style>
