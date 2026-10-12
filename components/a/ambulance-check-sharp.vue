<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="fj_bh9o0p"/><circle class="zka8v6b8o"/><circle class="otw2wcc-c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ambulance-check-sharp" /></template>
<style>
.fj_bh9o0p {
  d: path("M2.75 5.75v-1.5h13v3.5h2.705l.445.67l2.1 3.03l.249.283l.001.377V15H2.75v-1.5Zm13 2V15m-6.5-8.25v5.5M6.5 9.5H12");
}

.otw2wcc-c {
  cx: 17px;
  cy: 19.5px;
  r: 1.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zka8v6b8o {
  cx: 7.25px;
  cy: 19.5px;
  r: 1.5px;
}

</style>
