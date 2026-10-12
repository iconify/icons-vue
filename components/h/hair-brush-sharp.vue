<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="t__ca18uh"/><path class="dcwzxnz_k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hair-brush-sharp" /></template>
<style>
.dcwzxnz_k {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.5 6.75h.01m2.49 0h.01m2.49 0h.01M9.5 9.25h.01m2.49 0h.01m2.49 0h.01");
}

.t__ca18uh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 2.75h10V13H7zM11.25 13h2.25l-.05.75l-.4 6.75l-.05.75h-2l-.05-.75l-.4-6.75l-.05-.75z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
