<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="doki3kq2c"/><circle class="w6ucblb_v"/><path class="e_mqbzbed"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:eye-anatomy-sharp" /></template>
<style>
.doki3kq2c {
  d: path("M6.44 8.5a7 7 0 1 1 0 7c-2.19-1-2.19-6 0-7Z");
}

.e_mqbzbed {
  d: path("M19.5 12h1.75");
}

.w6ucblb_v {
  cx: 9.5px;
  cy: 12px;
  r: 1.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
