<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="pdtxn2b0t"/><path class="rwg8p3bcm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cargo-hold-sharp" /></template>
<style>
.pdtxn2b0t {
  d: path("M2.75 9h4.5m9.5 0h4.5M2.75 9l1.9 10.5l.222 1.764l1.778-.014h10.7l1.778.014l.222-1.764L21.25 9");
}

.rwg8p3bcm {
  d: path("M6.75 13.5h4v4h-4zm6.5 0h4v4h-4zM12 2.75V5.5m-2.25 0h4.5V10h-4.5z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
