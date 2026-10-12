<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="t4hoaxhpj"/><circle class="g2s802w8o"/><circle class="c1lhzj1ef"/><circle class="d2r6x9nmi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ai-brain-sharp" /></template>
<style>
.c1lhzj1ef {
  cx: 19.75px;
  cy: 12px;
  r: 1.5px;
}

.d2r6x9nmi {
  cx: 18px;
  cy: 18.75px;
  r: 1.5px;
}

.g2s802w8o {
  cx: 18px;
  cy: 5.25px;
  r: 1.5px;
}

.t4hoaxhpj {
  d: path("M11.25 4.6A3.25 3.25 0 0 0 5.5 6.25a3.25 3.25 0 0 0-1.75 5a3.75 3.75 0 0 0 .75 5.5a3.75 3.75 0 0 0 4 3.75l1.653.401L11.25 19.6Zm0 3.65h3.25l2.1-2.1M11.25 12h7m-7 3.75h3.25l2.1 2.1");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
