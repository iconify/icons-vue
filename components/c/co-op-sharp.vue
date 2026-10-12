<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="odauuo2hg"/><path class="psp7-dbpg"/><path class="l1fw9-yzn"/><path class="b-xqx5doo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:co-op-sharp" /></template>
<style>
.b-xqx5doo {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13.35 16.5h.01m4.79 0h.01");
}

.l1fw9-yzn {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.38 13.75h4.75a2.14 2.25 0 0 1 2.08 1.75l.77 3.6a1.33 1.4 0 0 1-2.24 1.3l-1.47-1.9h-3.04l-1.47 1.9a1.33 1.4 0 0 1-2.23-1.3l.76-3.6a2.14 2.25 0 0 1 2.09-1.75Z");
}

.odauuo2hg {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.88 3.75h4.75a2.14 2.25 0 0 1 2.08 1.75l.76 3.6a1.33 1.4 0 0 1-2.23 1.3L9.77 8.5H6.73l-1.47 1.9a1.33 1.4 0 0 1-2.23-1.3l.76-3.6a2.14 2.25 0 0 1 2.09-1.75Z");
}

.psp7-dbpg {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.85 6.5h.01m4.79 0h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
