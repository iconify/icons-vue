<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="c462uy5ip"/><path class="hjdx8ab3m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-circle-minus-corner-duotone" /></template>
<style>
.c462uy5ip {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M20 8H10a2 2 0 0 0-2 2v10l-5 1l1-5a8.945 8.945 0 0 1 16-8");
}

.ft5dv1b6b {
  fill: none;
}

.hjdx8ab3m {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m8 20l-5 1l1-5a8.944 8.944 0 1 1 16-8m-7 8h8");
}

</style>
