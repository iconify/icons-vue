<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="r92kb_bxl"/><path class="c3rqnjbvd"/><path class="s82rmm78o"/><circle class="g73u3bn-h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:deep-sea-sharp" /></template>
<style>
.c3rqnjbvd {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12.5 10.75h.01");
}

.g73u3bn-h {
  cx: 19.25px;
  cy: 4.25px;
  r: 1.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r92kb_bxl {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M19.75 10.75C18.25 8.25 15.25 7 12 7c-4 0-6.75 2-7.75 4.75l-1.5-2v8l1.5-2c1 2.75 3.75 4.5 7.75 4.5c3.25 0 6.25-1.25 7.75-3.75L16 13.75Z");
}

.s82rmm78o {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m16.75 12.25l.75 1.5m-.75 1.5l.75-1.5M11.5 7c.5-2.5 3-4 5.75-3.5");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
