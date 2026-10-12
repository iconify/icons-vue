<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ihlyl594y"/><path class="mprrb2w0g"/><path class="qj72olbzi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:boar-sharp" /></template>
<style>
.ihlyl594y {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 12.75V11.5l3.75-2l1.54-4.235l4.21-.765l1-1.5l1 1.5l1-1.25l.85 1.5c2.9 1 4.9 4 4.9 8v7.5h-2.5v-3h-7v3H9v-4c-2.5-.5-4.5-1.75-5.75-2.5l-.5-.333z");
}

.mprrb2w0g {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.5 13.25l-.776-1.94l2.026-.81");
}

.qj72olbzi {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.25 9.5h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
