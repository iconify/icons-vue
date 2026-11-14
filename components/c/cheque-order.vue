<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="at8epwdhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cheque-order" /></template>
<style>
.at8epwdhc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.2 19.5H2.5v-12h19v7.7M4 7.5v-3a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1v3m-13 3h.01m-.01 3h.01m-.01 3h.01M10 11h6.5m1.5 4v6m-3-3h6");
}

</style>
