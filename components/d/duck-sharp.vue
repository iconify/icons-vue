<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="jr3z08yhr"/><path class="m79p-gb9n"/><path class="t0v9_ux4u"/><path class="r4hgbcsyr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:duck-sharp" /></template>
<style>
.jr3z08yhr {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 11.75c1.75 1.25 3.75 1.5 6.25 1l-1.5-1.125V9.25a4 4 0 0 1 8 0v2l-1.25 1.25h5.25v2.75c0 3-2.75 5-6.25 5h-5c-3.25 0-5.5-3-5.5-8.5Z");
}

.m79p-gb9n {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.75 8.25h3.75l1.35-.006l-.9 1.006l-1.2 1.3l-1.219 1.3l-1.681-.4Z");
}

.r4hgbcsyr {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.25 15.5l3 2.143l3-2.143");
}

.t0v9_ux4u {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 8.5h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
