<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="u57yq2bni"/><circle class="uoogiib0w"/><path class="m6dfuopld"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:antivirus-shield-sharp" /></template>
<style>
.m6dfuopld {
  d: path("M12 6.5v1.75m0 6V16m-4.75-4.75H9m6 0h1.75M8.65 7.9l1.2 1.2m4.3 4.3l1.2 1.2m0-6.7l-1.2 1.2m-4.3 4.3l-1.2 1.2");
}

.u57yq2bni {
  d: path("m12 2.75l6.6 2.45l.652.244l-.002.696v5.26c0 4.4-2.9 7.6-7.25 9.85C7.65 19 4.75 15.8 4.75 11.4V6.14l-.002-.696L5.4 5.2Z");
}

.uoogiib0w {
  cx: 12px;
  cy: 11.25px;
  r: 2.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
