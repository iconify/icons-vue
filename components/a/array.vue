<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="r43b4tp0p"/><path class="fs5wvk5xm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:array" /></template>
<style>
.fs5wvk5xm {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 12h.01M12 12h.01m4.49 0h.01");
}

.r43b4tp0p {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 3.75h-2a1 1 0 0 0-1 1v14.5a1 1 0 0 0 1 1h2m10.5-16.5h2a1 1 0 0 1 1 1v14.5a1 1 0 0 1-1 1h-2");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
