<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="td_h78bej"/><path class="s386uebtx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bay-sharp" /></template>
<style>
.s386uebtx {
  d: path("m14.5 12l1.25-.904L17 12l1.25.904L19.5 12");
}

.td_h78bej {
  d: path("M2.75 2.75H12c3 0 6.5 1.75 7.5 4c-3.5-.25-8 1.25-8 5.25c0 3.5 4 5.25 9.75 5v4.25H2.75Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
