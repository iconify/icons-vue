<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="olnu_l0hu"/><path class="kxsjg9bia"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chisel-sharp" /></template>
<style>
.kxsjg9bia {
  d: path("m10.65 9.87l5.77-5.77l.35-.35l.47.16l3.24 1.07l.47.16l-.35.35l-7.16 7.16l-.35.35l-.35-.35l-2.09-2.08l-.35-.35z");
}

.olnu_l0hu {
  d: path("m10.92 10.82l1.56 1.56l1.41 1.41l-1.41 1.41l-3.94 3.94l-1.41 1.41l-1.42-1.41l-1.54-1.55l-1.42-1.41l1.41-1.42l3.94-3.93l1.41-1.42z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
