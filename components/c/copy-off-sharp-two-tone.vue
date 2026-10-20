<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="uf1ggp2pr"/><path class="gudpj20lw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:copy-off-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.gudpj20lw {
  d: path("M2 2L2 16.0001L5 16M22 22L8 22L8 8M1.7071 1.7071L22.2929 22.2929");
}

.uf1ggp2pr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M22.7071 22.7071C22.5198 22.8949 22.2653 23.0003 22 23L8 23C7.4477 23 7 22.5523 7 22L7 8C6.9997 7.7347 7.1051 7.4802 7.2929 7.2929L22.7071 22.7071ZM10.6569 7L22 7C22.5523 7 23 7.4477 23 8L23 19.3431L10.6569 7Z");
  stroke: none;
}

</style>
