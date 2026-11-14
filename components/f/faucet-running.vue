<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-mkjj_jn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:faucet-running" /></template>
<style>
.l-mkjj_jn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 5h11a5 5 0 0 1 5 5v1h-4v-1a1 1 0 0 0-1-1H4Zm5.5 0V2.5M7 2.5h5m6 8.5v4m0 2.75c1.75 1.75 1.75 3.75 0 3.75s-1.75-2 0-3.75Z");
}

</style>
