<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="ul2ad0bhm"/><path class="ey9f-lluv"/><path class="s84l2-b-l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gingerbread-man-sharp" /></template>
<style>
.ey9f-lluv {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 10h4.5l.95.32l3.35 1.11l.95.32l-.29.96l-.17.58l-.29.96l-.98-.17l-2.29-.41l-.98-.17l.22.98l1.31 5.79l.22.98h-3.5l-.36-.93l-.53-1.39L12 18l-.36.93l-.53 1.39l-.36.93h-3.5l.22-.98l1.31-5.79l.22-.98l-.98.17l-2.29.41l-.98.17l-.29-.96l-.17-.58l-.29-.96l.95-.32l3.35-1.11l.95-.32z");
}

.s84l2-b-l {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12.75h.01M12 15.5h.01");
}

.ul2ad0bhm {
  cx: 12px;
  cy: 5.25px;
  r: 2.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
