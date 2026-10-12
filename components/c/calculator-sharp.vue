<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="k8gsf-j4o"/><path class="s60-zgbca"/><path class="p962h-hlg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:calculator-sharp" /></template>
<style>
.k8gsf-j4o {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 2.75h14.5v18.5H4.75z");
}

.p962h-hlg {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.5 13h.01M12 13h.01m3.49 0h.01M8.5 17h.01M12 17h.01m3.49 0h.01");
}

.s60-zgbca {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 5.75h8.5v3.5h-8.5z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
