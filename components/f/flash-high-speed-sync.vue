<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="he3nq8bvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:flash-high-speed-sync" /></template>
<style>
.he3nq8bvz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.39 5.908l-3.074 4.966A1.393 1.393 0 0 0 11.5 13h.606a1.5 1.5 0 0 1 1.46 1.844L13 17.25a.946.946 0 0 0 1.67.795l4.149-5.369A1.35 1.35 0 0 0 17.75 10.5h-1.153A1.5 1.5 0 0 1 15.1 8.906l.15-2.406a1.006 1.006 0 0 0-1.86-.592M3 7h5.5m-6 5H6m-2 5h4.5");
}

</style>
