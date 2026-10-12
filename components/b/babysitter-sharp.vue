<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="zeo8pmb8i"/><path class="l4u0_mb7c"/><circle class="wrmaxej7p"/><path class="lefub1brs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:babysitter-sharp" /></template>
<style>
.l4u0_mb7c {
  d: path("M2.75 21.25V17.5a5 5 0 0 1 10 0v3.75Z");
}

.lefub1brs {
  d: path("M16 21.25v-1.5a2.5 2.5 0 0 1 5 0v1.5Zm-3.25-3l1.6 1.75L16 18.25");
}

.wrmaxej7p {
  cx: 18.5px;
  cy: 13.75px;
  r: 1.75px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zeo8pmb8i {
  cx: 7.75px;
  cy: 6.75px;
  r: 2.75px;
}

</style>
