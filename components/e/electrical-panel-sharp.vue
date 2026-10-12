<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="h-rwzfbii"/><path class="abvagh55i"/><path class="o83iu1bma"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:electrical-panel-sharp" /></template>
<style>
.abvagh55i {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.25 4.75l-3 3.25h3.5l-3 3.25m-3 2.5h6m-6 2.5h6m-6 2.5h6");
}

.h-rwzfbii {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 2.75h15.5v18.5H4.25z");
}

.o83iu1bma {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.25 13.75h.01m-.01 2.5h.01m-.01 2.5h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
