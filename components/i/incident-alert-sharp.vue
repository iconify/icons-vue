<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="nkokapkqk"/><path class="r8i1ocbvm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:incident-alert-sharp" /></template>
<style>
.nkokapkqk {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.95 4.76l7.35 13.73l.95 1.76H2.75l.95-1.76l7.35-13.73L12 3zM12 9v5.5");
}

.r8i1ocbvm {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 17.25h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
