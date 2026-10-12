<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="mo8e4vb8i"/><path class="rinhsubvt"/><path class="sfv0sabsu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bot-shield-sharp" /></template>
<style>
.mo8e4vb8i {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 2.75l6.6 2.45l.652.244l-.002.696v5.26c0 4.4-2.9 7.6-7.25 9.85C7.65 19 4.75 15.8 4.75 11.4V6.14l-.002-.696L5.4 5.2ZM12 9V7");
}

.rinhsubvt {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 9h7v5.5h-7z");
}

.sfv0sabsu {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.75 11.75h.01m2.49 0h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
