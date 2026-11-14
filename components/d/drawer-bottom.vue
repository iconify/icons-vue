<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uvm7mpb3b"/><path class="rxq3-1b3m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:drawer-bottom" /></template>
<style>
.rxq3-1b3m {
  d: path("M9.5 16.75v1h5v-1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uvm7mpb3b {
  d: path("M4 2.5h16v19H4ZM4 14h16");
}

</style>
