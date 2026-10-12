<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="ap6ytzn3r"/><path class="ceia8ccos"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cloud-gaming" /></template>
<style>
.ap6ytzn3r {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 10a2.5 2.5 0 0 1 0-5h.5a4 4 0 0 1 7 0H17a2.5 2.5 0 0 1 0 5Zm1.75 3.2h6.5a2.93 2.48 0 0 1 2.86 1.93l1.04 3.96a1.82 1.54 0 0 1-3.06 1.43l-2.01-2.09H9.92l-2.01 2.09a1.82 1.54 0 0 1-3.06-1.43l1.04-3.96a2.93 2.48 0 0 1 2.86-1.93");
}

.ceia8ccos {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.75 16.25h.01m6.49 0h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
