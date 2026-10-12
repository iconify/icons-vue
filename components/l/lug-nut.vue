<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="c6vt1lbds"/><path class="to8m3ibcr"/><path class="p3yr6jbrk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lug-nut" /></template>
<style>
.c6vt1lbds {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p3yr6jbrk {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.75 7.28l-.5.87q-.25.43-.75.43h-1q-.5 0-.75-.43l-.5-.87q-.25-.43 0-.86l.5-.87q.25-.43.75-.43h1q.5 0 .75.43l.5.87q.25.43 0 .86m4.9 3.56l-.5.87q-.25.43-.75.43h-1q-.5 0-.75-.43l-.5-.87q-.25-.43 0-.86l.5-.87q.25-.43.75-.43h1q.5 0 .75.43l.5.87q.25.43 0 .86m-1.87 5.76l-.5.87q-.25.43-.75.43h-1q-.5 0-.75-.43l-.5-.87q-.25-.43 0-.86l.5-.87q.25-.43.75-.43h1q.5 0 .75.43l.5.87q.25.43 0 .86m-6.06 0l-.5.87q-.25.43-.75.43h-1q-.5 0-.75-.43l-.5-.87q-.25-.43 0-.86l.5-.87q.25-.43.75-.43h1q.5 0 .75.43l.5.87q.25.43 0 .86m-1.87-5.76l-.5.87q-.25.43-.75.43h-1q-.5 0-.75-.43l-.5-.87q-.25-.43 0-.86l.5-.87q.25-.43.75-.43h1q.5 0 .75.43l.5.87q.25.43 0 .86");
}

.to8m3ibcr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
