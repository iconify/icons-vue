<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="af9r0cicv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:grain-bin" /></template>
<style>
.af9r0cicv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 20.65v-9.3q0-.6-.6-.6h-.3q-.6 0-.13-.37l8.31-6.51q.47-.37.94 0l8.31 6.51q.47.37-.13.37h-.3q-.6 0-.6.6v9.3q0 .6-.6.6H4.85q-.6 0-.6-.6m0-9.9h15.5M8 13.75v4.5m4-4.5v4.5m4-4.5v4.5");
}

</style>
