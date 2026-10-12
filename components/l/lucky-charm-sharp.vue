<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="o20y7lbfc"/><path class="lf-yftbhc"/><path class="i1woqibsa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lucky-charm-sharp" /></template>
<style>
.i1woqibsa {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 12.75l.33 2.42l2.42.33l-2.42.33l-.33 2.42l-.33-2.42l-2.42-.33l2.42-.33z");
}

.lf-yftbhc {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.89 8.53h.01m2.85-3.41h.01m6.49 0h.01m2.85 3.41h.01");
}

.o20y7lbfc {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 10.75a8 8 0 0 1 16 0v10.5h-3v-10.5a5 5 0 0 0-10 0v10.5H4V20Z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
