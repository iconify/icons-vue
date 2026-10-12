<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="zvd0-_b_k"/><path class="jtlv78mkq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:esim-sharp" /></template>
<style>
.jtlv78mkq {
  d: path("M6.75 12.75h6.5v5.5h-6.5zm0 2.75h6.5m1.65-9.44l2.583.457l.457 2.583m-2.52-6a6.75 6.75 0 0 1 5.48 5.48");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zvd0-_b_k {
  d: path("M5.25 7.75h7l1.06 1.06l1.88 1.88l1.06 1.06v9.5H3.75V7.75z");
}

</style>
