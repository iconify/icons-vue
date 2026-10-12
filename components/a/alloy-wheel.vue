<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="c6vt1lbds"/><path class="ivkpj17ol"/><path class="rjgzvlbec"/><path class="to8m3ibcr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:alloy-wheel" /></template>
<style>
.c6vt1lbds {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ivkpj17ol {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 5.1a6.9 6.9 0 1 0 0 13.8a6.9 6.9 0 0 0 0-13.8");
}

.rjgzvlbec {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.43 9.12l-.57-1.15q-.27-.53.21-.18l2.6 1.89q.49.35-.11.26l-1.26-.2q-.6-.09-.87-.62m1.75 3.35l.91-.9q.43-.42.25.15l-1 3.05q-.18.57-.28-.02l-.21-1.26q-.09-.59.33-1.02m-2.65 2.7l1.14.59q.54.28-.06.28h-3.22q-.6 0-.06-.28l1.14-.59q.53-.27 1.06 0m-3.38-1.68l-.21 1.26q-.1.59-.28.02l-1-3.05q-.18-.57.25-.15l.91.9q.42.43.33 1.02m.55-3.75l-1.26.2q-.6.09-.11-.26l2.6-1.89q.48-.35.21.18l-.57 1.15q-.27.53-.87.62");
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
