<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rs_t0gbby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:furniture-polish" /></template>
<style>
.rs_t0gbby {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 13V4.5a2 2 0 0 1 2-2h5a2 2 0 0 1 2 2V13m-11 0h13v3h-13Zm2 3v5.5m9-5.5v1.1m0 3.8v.6M19 16q1 2 3 3q-2 1-3 3q-1-2-3-3q2-1 3-3Z");
}

</style>
