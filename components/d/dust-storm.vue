<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="l3fgv0bcu"/><path class="h9yuqlxrb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dust-storm" /></template>
<style>
.h9yuqlxrb {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.75 7.5h.01m3.74-2.25h.01M20.75 12h.01m-2.26 4.5h.01m-8.01 4h.01m4.24 0h.01");
}

.l3fgv0bcu {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 7.5h9.5M2.75 12h14.5m-11.5 4.5h9");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
