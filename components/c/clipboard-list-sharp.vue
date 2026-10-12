<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="id6hjqbni"/><path class="vxzk7mbdt"/><path class="ekmihcb8x"/><path class="bjth-8b6g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:clipboard-list-sharp" /></template>
<style>
.bjth-8b6g {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.5 11h3.75m-3.75 4h3.75");
}

.ekmihcb8x {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.75 11h.01m-.01 4h.01");
}

.id6hjqbni {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 4.25h-4v17h14.5v-17h-4");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.vxzk7mbdt {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 2.75h6.5v3.5h-6.5z");
}

</style>
