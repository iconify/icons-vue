<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xxrjbccza"/><path class="nt0whubxd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fencing-sabre" /></template>
<style>
.nt0whubxd {
  d: path("M4.5 12.5a5 5 0 0 1 7 7M8 16l-3.5 3.5m7 0q-3.5 2.5-7 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xxrjbccza {
  d: path("M11 13q4-2.5 10.5-10.5");
}

</style>
