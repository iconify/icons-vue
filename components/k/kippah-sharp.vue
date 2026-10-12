<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="f9qxmtqli"/><path class="m9me6bb5j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:kippah-sharp" /></template>
<style>
.f9qxmtqli {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 15.5a9.25 9.25 0 0 1 18.5 0v2.25H2.75V16Zm0-.25h18.5");
}

.m9me6bb5j {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 9.5h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
